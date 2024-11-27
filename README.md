RBAC-UI
User Management Role-Based Access Control (RBAC) System
RBAC-UI is a React-JS application that provides an intuitive interface for managing users, roles, and permissions in a Role-Based Access Control (RBAC) system. The project focuses on user-friendliness, responsiveness, and maintaining data persistence with localStorage.

Overview
This project is a frontend-only solution for handling user and role management, with features for adding, editing, and removing users and roles. Administrators can seamlessly view and assign roles with permissions while ensuring a clear, responsive, and organized workflow.

Key Features
User Management: Add, edit, or remove users. Assign roles and update user status (Active/Inactive).
Role Management: Define roles and assign permissions like Read, Write, and Delete. Customize role attributes for flexibility.
Permission Control: Dynamically assign and visualize permissions for better understanding.
Mock API Simulation: Simulates API responses to provide a real-time experience.
Responsive Design: Compatible across desktop and mobile platforms for smooth interaction.
Persistent Storage: Uses localStorage to retain user and role data across sessions.
Technologies Implemented
Frontend Framework: React
Styling: Tailwind CSS
State Management: React hooks (e.g., useState, useReducer)
Mock API: Simulated with JSON or local JavaScript functions
LocalStorage Integration: For data persistence
Setup and Installation
Follow the steps below to set up and run the project locally.

Prerequisites
Ensure Node.js and npm are installed.
Steps
Clone the Repository:
bash
Copy code
git clone https://github.com/dubeyhars/RBAC-UI.git
Install Dependencies:
bash
Copy code
npm install
Run the Application:
bash
Copy code
npm start
Access the app in your browser at http://localhost:3000.
How It Works
Add a Role
Navigate to the Role Management section.
Click Add Role and define a role (e.g., Admin, Editor).
Assign permissions (Read, Write, Delete) and save the role.
Add a User
Open the User Management section.
Click Add User, fill out the form, and assign a role from the dropdown.
Set the user’s status to Active/Inactive and save the user.
Edit or Delete
Use the Edit button to modify user details.
Use the Delete button to remove users or roles.
LocalStorage Integration
Data is stored in the browser’s localStorage, ensuring persistence even after refreshing the page.
Usage
Manage Users: Add, edit, or delete user records.
Configure Roles: Define roles and customize their permissions.
Adjust Permissions: Update permissions dynamically with ease.
Acknowledgments
This project has been a great learning experience, enhancing my understanding of React development and system design. I look forward to contributing to similar innovative projects in the future.
