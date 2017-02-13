# node-express-mongo-api
simple project with Node.js, the Express framework, and MongoDB, focusing on the fundamental REST routes and basic database interaction

## use 
*  Install dependencies
    ```
    npm install
    ```
*  In a directory config in the root of your project, create a db.js file
    ```
    mkdir config 
    cd config
    touch db.js
    ```
    Inside, add the URL:
    ```
    module.exports = {
      url : //YOUR MONGODB URL HERE
    };
    ```
*  Start server
    ```
    npm run dev
    ```
