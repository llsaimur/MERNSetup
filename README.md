The skeleton application will encapsulate rudimentary features and a workflow that's
repeated for most MERN applications. This is a skeleton structure as a basic but fully
functioning MERN web application with user create, read, update, delete (CRUD),
and authentication-authorization (auth) capabilities; this will also demonstrate how
to develop, organize, and run code for general web applications built using this
stack. The aim is to keep the skeleton as simple as possible so that it is easy to extend
and can be used as a base application for developing different MERN applications.
To restrict and protect access to user API endpoints according to the skeleton features we will use JWT.

Backend implementation of the MERN skeleton using Node, Express, and MongoDB:
  Overview of the skeleton application
  Backend code setup
  User model with Mongoose
  User CRUD API endpoints with Express
  User Auth with JSON Web Tokens
  Running backend code and checking APIs

Feature breakdown:
In the skeleton application, the following use cases with user CRUD and
auth functionality implementations are:
  Sign up: Users can register by creating a new account using an email
  address.
  User list: Any visitor can see a list of all registered users.
  Authentication: Registered users can sign-in and sign-out.
  Protected user profile: Only registered users can view individual user
  details after signing in.
  Authorized user edit and delete: Only a registered and authenticated user
  can edit or remove their own user account details.

  Please feel free to use this and start building your own app! :)

  ***
To use it, clone it.
Once you have the code, go on terminal and type:
yarn
--this is to install all node modules/dependencies needed for the project...
run development
--this is to run the project, to open go on your browser and type http://localhost:3000/

