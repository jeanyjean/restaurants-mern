# Restaurants Reviews
By Purich Trainorapong 6210545581

Restaurants reviews web application using MERN stacks later convert Backend to Serverless with MongoDB Realm.

This was created with this [tutorial](https://www.youtube.com/watch?v=mrHNSanmqQ4) from freeCodeCamp as guide and upgraded it with new React version.

Visit the website [here](https://restaurant-reviews-qzsih.mongodbstitch.com/)
## Getting Started
1. Install backend dependencies
```
cd backend
npm i -g nodemon
npm i
```
2. Install frontend dependencies
```
cd ..
cd frontend
npm i
```
3. Create .env file in backend folder for information on your database
```
RESTREVIEWS_DB_URI= URI of your database
RESTREVIEWS_NS= Name of your collection
PORT= port number for the server to run on
```
## Run locally
1. Run backend server (No longer needed)
```
cd backend
nodemon server
```
2. Run frontend page
```
Open a new terminal
cd frontend
npm start
```
3. Open http://localhost:3000/ on your preferred browser
