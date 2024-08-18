# demoSetup-MEAN
A Development setup for MEAN Stack 

1. Install MongoDB Community Server & Mongoose Compass Client in local:
   URL: https://www.mongodb.com/try/download/community
   URL: https://www.mongodb.com/try/download/compass

   Once your MongoDB server is installed and running you can connect to it using 
   mongoDB Compass GUI client or Shell on the default port 27017
   using: mongodb://localhost:27017, and create a database AuthDB.

2.  Make a project directory in [drive]:\demo\meanstack-auth
3.  start VSCode by 'code .'
4.  Create two sub-dir in the project dir by name: 'api' and 'client'
5.  Open Integrated Terminal under 'api' and run npm init -y
6.  Install express nodemon dotenv mongoose, using npm i express nodemon dotent mongoose --save
7.  Add a line of code "type": "module", anywhere in package.json file, this will let you load ES Module
   allowing to import modules instead of required them.
8.  Also add "start": "nodemon index.js" in scrips of package.json, so that express can be started using 'npm start' and it restart every time a file changes.
9. Create index.js in api folder and import express, mongoose, dotenv in index.jsn
10. Make the app listen on port 8800
11. Make the app connect to MongoDB using mongodb://127.0.0.1:27017/AuthDB
