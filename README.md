# Getting Started with uploader App

# To start the Backend app run the below command inside (server folder)

### `npm install express`
### `node index.js` (will start the backend) [express js]

To check the api's load this below api in browser
Api:  http://localhost:5000/

# To start the react run the below command in (frontend folder) [react js]

### `npm install`
### `npm run start` (will start the frontend)

Runs the app and open the below url to go to git diff
Open http://localhost:3000/ to open login page
Register from there and it will redirect to the post page to upload your images

 # how this app works?
  1) User will be redirected to login page as default home page
  2) And he/she can create their own access and based on it they can login
  3) It redirects to the post page there they can upload the images and each uploaded image will be added in the gallery component
     
 # storage
  1) Each user login data is being maintained in a json file (user. json) which will be updated when new user register
  2) Images are being stored in separate repos with their respective mail id as there folder name (richard.gmail.com) and all their images are maintained separately
  3) In local storage which holds the login authentication.

# todo (can't able to do due to time constraints)
 1) Socket. IO need to be created and when new user uploads an image it will be reflected in current users posts via open connection for the logged in user
 2) Just need to be updated in login configs
 3) Also need to convert the json storage method into mongodb storage
 4) Deployment was in progress I have created a yml file in a git work flow and working on publishing the app
 5) And finally code needs to update and env, config files need to be created
