# Assignment 2 Taskmaster amirulz
Assignment 2 Taskmaster amirulz


# TaskMaster Pro API

RESTful API built using ExpressJS, Sequelize, and PostgreSQL.

## Installation

git clone https://github.com/amirulzuraik97-code/assignment-2-taskmaster-amirulz

cd assignment-2-taskmaster-amirulz

npm install

## Environment Variables

Create .env file

DB_HOST=localhost
DB_USER=postgres
DB_PASSWORD=password
DB_NAME=taskmaster
PORT=3000

## Run Server

npx nodemon server.js

## API Endpoints

Users

POST /users  
GET /users  
GET /users/:id  
DELETE /users/:id  

Tasks

POST /tasks  
GET /tasks  
GET /tasks/:id  
PUT /tasks/:id  
DELETE /tasks/:id
