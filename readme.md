# MEARN App

# .env

create `.env` file and place following variable in it

MONGO_URI = 'URI of your mongo database with password and database name'
JWT_SECRET= 'secret key of your choice'

# Server.js

main file of Server

# Routers

`goalRoutes` router for _GET_, _POST_, _PUT_ and _DELETE_ request
`userRoutes` router

# Controller

`goalController.js` contain _function_ to go to **_GET, POST, PUT_** and **_DELETE_** requests

# Models

`goalModel.js` to define Schema and its field of Goals for database
`userModel.js` to define Schema and its field of Users for database

# MiddleWare

`errorMiddleware.js` for error handling in development environmet

# Config

`db.js` for connection of db using mongoose
