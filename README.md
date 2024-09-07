# Task Manager Application

A simple full-stack application that allows users to manage a list of tasks with basic user authentication. The application includes a React.js frontend and a Node.js + Express.js backend. The app also supports user registration and login functionality.
![image](https://github.com/user-attachments/assets/cf31b4c8-f639-438a-8c4f-b33eee394ee7)

![image](https://github.com/user-attachments/assets/b8254f9e-182b-4c2a-8521-db6597a34efa)

![image](https://github.com/user-attachments/assets/acdc6c8b-2b46-42c4-adb3-f62696ad9f64)

![image](https://github.com/user-attachments/assets/89b8344e-39f0-4b9a-9592-fb696683fdc7)

![image](https://github.com/user-attachments/assets/2dc96969-de9a-4c3c-8b66-e9f5f03863c4)





## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Setup Instructions](#setup-instructions)
4. [API Endpoints](#api-endpoints)
## Features

- Manage tasks (create, read).
- User authentication (register, login).
- Protected routes based on user authentication.
- Deployment on cloud platforms (Heroku for backend, Netlify for frontend).

## Tech Stack

- **Frontend**: React.js (with Hooks)
- **Backend**: Node.js, Express.js
- **Styling**: CSS
- **Deployment**: Heroku, Netlify

## Setup Instructions
1. Install all the dependencies

   ```sh
   npm run install
   ```

2. Start the frontend

   ```sh
   npm start
   ```
   
3. Go to http://localhost:3000

4. Start the Backend: Firt go into the backend folder of this Fullstack app
    ```sh
   cd ../backend
   ```
5. Now Start The backend server:
   ```sh
   node index.js
   ```

## API Endpoints:

**Task Management**

**1.** GET /tasks: Fetch all tasks.

**2.** POST /tasks: Add a new task.


**Authentication**

**1.** POST /register: Register a new user.

**2.** POST /login: Authenticate a user and receive a token.



