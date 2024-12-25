# Task Management System

## Description
This is a task management system that allows users to create, update, delete, and change the status of tasks. The system sends email notifications to a predefined email address whenever a task's status is updated.

## Features
- Add new tasks with a title and description.
- Update the status of tasks (To Do, In Progress, Done).
- Delete tasks.
- Sends email notifications upon task status updates.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Email Notifications:** Nodemailer

## Setup Instructions

1. **Download the Project**
   Download all project files and place them in a local directory.

2. **Install Dependencies**
   Navigate to the backend folder and install the required packages:
   ```bash
   cd backend
   npm install


## Set Up MongoDB

-Use your MongoDB connection URL in the server.js file.
-Ensure MongoDB is properly set up and running.

## Configure Email Notifications

Update the email sender and recipient details in server.js.
Use an app password for secure email functionality.

## Run the Backend Server Start the backend server with the following command:

node server.js



## Open the Frontend Open the index.html file in your browser to interact with the application.


# API Endpoints
Tasks API
GET /api/tasks


