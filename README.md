## Introduction
This project is to demonstrate to build and run Full Stack MERN Application using React, Node.js, Express & MongoDB. MongoDB cluster is created using MongoDB Atlas on a Google Cloud. 

**Prerequisites**
1. Create a Cluster using MongoDB Atlas and Google cloud
2. Whitelist local ip address for certain period to use for this application
3. Save the MongoDB connection url

**Steps to run the application:**
1. clone the project
2. Update the CONNECTION_URL with the relevant MongoDB URL in ../server/index.js
3. Terminal One: Navigate to client and run npm install then npm start
4. Terminal Two: Navigate to server and run npm install then npm start
5. MongoDB should be listening to port 5000: http://localhost:5000
6. ReactJS application should be listening to port 3000: http://localhost:3000
