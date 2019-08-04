# Face Recognition App

This is the back-end part of a full face recognition app, based on Nodejs, Express, and Heroku. You can easily Sing in or Register with your credentials [here](https://nikos-face-rec-app.herokuapp.com/).

# Components
### Server & Database
To set up a server for app and API:
* Express.js 
* Nodejs 

The database based on:
* PostgreSQL
* Created and Deploy via Heroku tools


### Details:
* Connection between the server and the database was created using Knex.js 
* To ensure that the password of any user is protected we used bcrypt
* Database stores **only** the name, email, and encrypted password. 
* Git as a source control method
* Heroku to deploy project online 