
## React Messenger Application

This application was created as part of CSC 667 at SFSU. It is a simple messaging application created in React that allows users to communicate in private and group conversations. It was developed as a group project and the collaborators are listed on the repository.

Before you are ready to run this application, please open MongoDB and Redis in local environment. 

Then, you will need to run the following commands consecutively：

### `npm install`

It will take a while until all the dependency packages are properly installed

### `npm run build`

Necessary to run the frontend.js file

### `sudo node gateway.js`

"sudo" is recommended. For some local development environment, error will thrown without "sudo"

### `node messenger.js`

You need to run this command so that this service can be linked to MongoDB to communicate message data.

### `node user.js`

To keep this service on to ensure user login and register functions.

### `node websocket.js`

To run websocket.js to make sure the real-time updating between different users.

### `node frontend.js`

Static file serving

This is the final step to initialize this React application.
Then you can visit via http://localhost:4000



