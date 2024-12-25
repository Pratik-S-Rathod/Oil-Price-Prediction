# Task Management System

## Overview
This is a simple Task Management System that allows users to:
- Add tasks with a title and description.
- Update the status of tasks.
- Delete tasks.
- Receive email notifications when a task's status is updated.

## Features
- **Backend**: Built with Node.js, Express, and MongoDB.
- **Frontend**: Basic HTML, CSS, and JavaScript for user interaction.
- **Email Notifications**: Sends email updates when the status of a task changes.

---

## Prerequisites
1. **Node.js**: Ensure Node.js is installed on your system.
2. **MongoDB Atlas**: Set up a free MongoDB Atlas cluster or use a local MongoDB instance.
3. **Email Setup**: Use a Gmail account with an app password for email notifications.

---

## Setup Instructions

### 1. Clone or Download the Project
Download all project files to your local system.

### 2. Backend Setup
- Navigate to the backend folder:
  ```bash
  cd backend
  ```
- Install dependencies:
  ```bash
  npm install
  ```
- Configure MongoDB and Email:
  - Update `server.js` with your MongoDB connection string and Gmail credentials.
  
- Start the server:
  ```bash
  node server.js
  ```
  The backend will run on `http://localhost:5001`.

### 3. Frontend Setup
- Open the `index.html` file in your browser.

---

## Usage

### Add a Task
1. Enter the title and description in the input fields.
2. Click the "Add Task" button.

### Update Task Status
1. Use the dropdown menu beside each task to select the new status.
2. The status will be updated, and an email notification will be sent.

### Delete a Task
1. Click the "Delete" button next to the task.

---

## File Structure
```
project-directory
├── backend
│   ├── server.js
│   └── package.json
├── frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
```

---

## Notes
- Use the Gmail app password for secure email notifications.
- Ensure the backend server is running before using the frontend.
- MongoDB should be connected properly to store and retrieve tasks.

