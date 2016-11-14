##Instagram
a. login with facebook => facebook login page
  Method:GET
  Data: Username, Password

b. facebook login page => Server
  Method: POST
  Data: Username, Password

c. Server => Home page
  Method: GET
  Data: People you are following, Post they made

d. Like a Image = >Server
  Method: POST
  Data: user_id/Username, Post_id

f. Search Entry => Server
  Method: GET
  Data: Search query

g.Submit photo => Server
  Method:POST
  Data: Image, Caption, Location, TAGS

h. Server => following
  Method: GET
  Data: Following recent follows, following recent likes

i. Server => profile page
  Method : GET
  Data: Profile pic, Username, Description, number of followers, number of following, number of posts, all photos
