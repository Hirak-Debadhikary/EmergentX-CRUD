<h1>Todo Application README -</h1> 
This README provides instructions on how to set up and run the Todo application, which is built using React.js, Chakra-UI for the front end, and Node.js, Express.js, and MongoDB for the backend. The application allows users to perform CRUD (Create, Read, Update, Delete) operations on tasks.

<h2>Table of Contents -</h2> 
<h4>Prerequisites -</h4> 

- Installation
- Configuration

<h2>Before you begin, ensure you have met the following requirements:</h2>  
- Node.js: Make sure you have Node.js installed on your machine. You can download it from https://nodejs.org/.
- MongoDB: You will need a running MongoDB server. You can download and install MongoDB from https://www.mongodb.com/try/download/community or use a cloud-hosted MongoDB service.

<h2>Installation -</h2>

<h4>Clone this repository to your local machine using Git:</h4>
- bash
- git clone https://github.com/Hirak-Debadhikary/EmergentX-CRUD.git

<h4>Navigate to the backend folder:</h4>
- bash
- cd backend

<h4>Install backend dependencies by running the following command:</h4>
- bash
- npm install

<h4>Return to the root folder:</h4>
- bash
- cd ..

<h4>Navigate to the frontend folder:</h4>
- bash
- cd frontend

<h4>Install frontend dependencies by running the following command:</h4>
- bash
- npm install
- Configuration
- Backend Configuration

<h4>Create a .env file in the backend folder:</h4>
- PORT=<Your-Port>
- MONGODB_URI=<Your-Mongodb-Uri>
- Replace <your-mongodb-uri> with the connection URI for your MongoDB database.

<h4>Frontend Configuration</h4>
- No additional configuration is required for the front end.

<h4>Running the Backend Server</h4>
- Start the backend server by navigating to the backend folder and running:
- bash
- cd backend
- npm start
- This will start the Node.js server on your port.

<h4>In a separate terminal, navigate to the frontend folder and start the React development server:</h4>
- bash
- cd frontend
- npm start
- This will start the React application on port 3000 and open it in your default web browser.

<h4>Usage</h4>
Once the application is running, you can access it in your web browser at http://localhost:3000. You can perform the following CRUD operations:

- Create: Add new tasks by entering the task description and clicking the "Add Task" button.

- Read: View the list of tasks on the main page.

- Update: Click the "Edit" button next to a task to edit its description.

- Delete: Click the "Delete" button next to a task to remove it from the list.
