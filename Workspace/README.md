# MERN ToDo Application
A simple full-stack ToDo application built using MongoDB, Express, React, and Node.js.This is a final project for the LUT University Moodle course, built using the MERN stack.

**#Project Overview**

The goal of this project is to build a functional full-stack web application that connects a React frontend with a Node/Express backend and stores data in MongoDB.

**Users can:**

Add new tasks with a title and description
View all existing tasks
Edit tasks directly from the UI
Delete tasks with confirmation
It allows users to create, update, and delete tasks.


**#Frontend**

React (Hooks: useState, useEffect)
Bootstrap (UI styling)
Fetch API (for HTTP requests)

**#Backend**

Node.js
Express.js
MongoDB
Mongoose
CORS middleware

**## Features**
- Add tasks
- Edit tasks
- Delete tasks
- View all tasks

Create new todo items
Read and display all todos from database
Update existing todos
Delete todos
Inline editing support
Basic success and error handling
Real-time UI updates without page refresh



**## Tech Stack**
- React
- Node.js
- Express
- MongoDB

****## Installation**
**### Backend****
cd backend
npm install
node server.js

**### Frontend**
cd frontend
npm install
npm start

**## Usage**
1. Open frontend in browser
2. Add a task
3. Edit or delete tasks
4. Data is stored in MongoDB
Backend Setup
cd backend
npm install
node server.js

**#MongoDB connection:**

mongodb://localhost:27017/mern-app

**#Backend runs on:**

http://localhost:8000
Frontend Setup
cd frontend
npm install
npm start

**#Frontend runs on:**

http://localhost:3000
API Endpoints
**Method	Endpoint	Description**
GET	      /todos	    Fetch all todos
POST	  /todos	    Create todo
PUT	      /todos/	    Update todo
DELETE	  /todos/  	    Delete todo


**#Project Structure**
project-root/
├── backend/
│   ├── server.js
│   ├── package.json
│
└── frontend/
    ├── src/
    │   ├── Todo.js
    │   ├── App.js
    │   └── index.js

**Key Learning Outcomes**
Building REST APIs with Express
Connecting MongoDB with Node.js using Mongoose
Managing React state using hooks
Full-stack CRUD application flow
Frontend and backend integration

**Notes**
This is a course project for learning purposes
MongoDB runs locally
UI is intentionally kept simple using Bootstrap
No authentication system included

**Future Improvements**
Add authentication (login/register)
Improve UI design with Tailwind or Material UI
Deploy project online (Vercel / Render)
Add task completion status
Use environment variables for configuration

**Name: Sonali Diwakar**
Course: LUT University – Moodle MERN Final Project
Year: 2026