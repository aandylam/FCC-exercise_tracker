# Exercise Tracker

This is a Node.js API with MongoDB and Mongoose to track exercises. The API supports the following actions:
- Creates a new user with a POST request to /api/users
- Gets a list of all users with a GET request to /api/users
- Adds exercises with a POST request to /api/users/:_id/exercises
- Can retrieve exercise log of any user with a GET request to /api/users/:_id/logs

To run this API, clone this repository as well as making sure you have Node/MongoDB/Mongoose installed. Simply run *npm start* to activate local server.
