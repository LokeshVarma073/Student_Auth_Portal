Student Portal Authentication System 🔐

A secure web-based Student Portal Authentication System developed using Node.js, Express.js, HTML, CSS, and JavaScript. This project provides secure user registration, login, password hashing, JWT-based authentication, token verification, protected route access, and role-based authorization.

🚀 Features

User Registration: Allows students to create accounts.

User Login: Authenticates users using email and password.

Password Hashing: Uses bcrypt to securely hash passwords.

JWT Token Generation: Generates JSON Web Tokens after successful authentication.

Protected Routes: Restricts access to authenticated users.

User Authorization: Implements role-based access control.

Token Verification: Verifies JWT signatures and expiration.

Student Dashboard: Provides access to courses and academic records.

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express.js

Authentication: JSON Web Token (JWT)

Password Security: bcrypt

Data Storage: JSON File

⚙️ Installation and Setup

Clone the repository:

git clone YOUR_REPOSITORY_URL

Navigate to the project folder:

cd student-portal-auth

Install dependencies:

npm install

Create .env from .env.example and configure your JWT secret.

Start the server:

npm start

Open your browser:

http://localhost:3000

🔒 Security Implementation

Bcrypt password hashing

JWT-based authentication

Token expiration

Protected API endpoints

Role-based authorization

Server-side token verification

🎯 Project Objective

The main objective is to develop a secure student portal that ensures only authenticated and authorized users can access protected academic resources, personal profiles, and course materials.

Project Type: Full Stack Web Development
Status: Completed – Educational Demo