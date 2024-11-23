# TaskMaster - Task Management System
TaskMaster is a full-stack web application designed to help users efficiently manage their daily tasks. With features like user registration, task creation, updates, filtering, and search capabilities, TaskMaster provides an intuitive and user-friendly interface for personal and professional task management.

# Project Overview
TaskMaster is built to demonstrate practical full-stack development skills by integrating backend technologies (Node.js, Express.js, MongoDB) with frontend technologies (HTML, CSS, JavaScript). The application is designed to be scalable, secure, and optimized for performance.

# Features
User Registration and Authentication
Secure registration and login with password hashing using bcrypt.
Authentication using JSON Web Tokens (JWT).

# Task Management
Create tasks with attributes such as title, description, deadline, and priority.
Update and delete tasks seamlessly.

# Task Filtering
Filter tasks by priority (low, medium, high) or due date.

# Search Functionality
Search tasks by keywords in the title or description.

# Responsive Design
Fully responsive user interface optimized for desktops, tablets, and mobile devices.

# Error Handling
Proper error messages for form validation and server-side issues.

# Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT), bcrypt

# Installation
Prerequisites:
Node.js (v16.x or higher)
MongoDB (Ensure a running MongoDB instance)
A web browser (e.g., Chrome, Firefox)

# Steps

# Clone the repository:
git clone https://github.com/your-username/TaskMaster.git

# Navigate to the project directory:
cd TaskMaster

# Install dependencies:
npm install

# Create a .env file in the project root and add the following environment variables:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

# Start the server:
npm start

# Open your browser and navigate to:
http://localhost:5000

# Usage
Signup: Create a new account using the signup page.
Login: Log in with your registered email and password.
Manage Tasks:
Create tasks by entering a title, description, deadline, and priority.
Update tasks when necessary.
Delete tasks you no longer need.
Filter and Search:
Use the filter dropdown to sort tasks by priority or deadline.
Use the search bar to find tasks based on keywords.

# Project Structure
TaskMaster/
├── public/           # Static files (HTML, CSS, JS)
├── views/            # Frontend templates
├── routes/           # API routes
├── models/           # Mongoose schemas
├── controllers/      # Application logic
├── config/           # Configuration files
├── .env              # Environment variables
├── server.js         # Entry point of the app
└── README.md         # Documentation

# Future Improvements
Add email notifications for task deadlines.
Implement dark mode for the user interface.
Enhance task prioritization with drag-and-drop features.
Integrate social logins (e.g., Google, Facebook).

# Contributing
Contributions are welcome! If you'd like to contribute, follow these steps:
Fork the repository.

Create a feature branch:
git checkout -b feature-name

Commit your changes:
git commit -m "Add feature name"

Push to the branch:
git push origin feature-name
Open a pull request.

# License
This project is licensed under the MIT License.
