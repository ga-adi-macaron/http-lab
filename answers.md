Youtube App

a. Login => Homepage
  1. Method: Post
  2. Data: Username, Password, and/or Email, Password.
  
b.Homepage => Video page
  1. Method: Get
  2. Data input: query in the path form: "watch?v=video_id"
  3. Data return: outputstream for video
  
c. Homepage => Upload screen
  1. Method: Post
  2. Data: User, Video file.
  
d. Videopage (Change quality)
  1. Method: Get
  2. Data input: Quality preference (e.g. 720, 480)
  3. Data output: outputstream for video of selected quality
  
e. Videopage (Post/remove comment)
  1. Method: Post
  2. Data: User_id, comment string, video_id
 
f. Videopage (Toggle like or subscribe)
  1. Method: Post
  2. Data: User_id, like/subscribe toggle_value, video_id/channel
