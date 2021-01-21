## REST exercise

You are asked to build an API for a photo app.
You need to create the routes according to REST for the following actions:


The end-user wants to see a list of photos

get /photos/


The end-user wants to see a particular photo

get /photos/:id


The end-user wants to upload a new photo

get /photos/new
post /photos


The end-user wants to update an existing photo

#### display form to user. user needs to fill it out
get /photos/:id/edit
#### update the database
put /photos/:id


The end-user wants to see a list of user profiles

get /users/


The end-user wants to see a specific profile

get /users/:id


The end-user wants to see a list of the photos for a specific profile

get /users/:id/photos/


The end-user wants to see one particular photo of a particular user

get /users/:user_id/photos/:id


You need to write the route with a verb and a path. You don't need to implement the functionality.
For example, to get a list of users, you just need to write GET '/users'. No need to write the code to get the actual users.
