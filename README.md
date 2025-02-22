Task Management System

🚀 Project Overview

The Task Management System is a web application that allows users to create, update, delete, and manage tasks efficiently. It supports authentication, JWT-based authorization, role-based access control (RBAC), and caching using Redis. The system also includes a cron job for logging task counts.

🛠️ Tech Stack

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ODM)

Authentication: JWT (JSON Web Token)

Caching: Redis

Deployment: Render/Railway (for backend)

API Testing: Thunder Client/Postman

📌 Features

✅ User Authentication (Register, Login)✅ JWT-Based Authorization✅ Role-Based Access Control (Admin, User)✅ CRUD Operations for Tasks and Categories✅ Redis Caching for Performance Optimization✅ Cron Job for Logging Task Counts✅ API Endpoints for Task Management

🔧 Installation & Setup

1️⃣ Clone the Repository

git clone <your-repo-url>
cd task-management-system

2️⃣ Install Dependencies

npm install

3️⃣ Set Up Environment Variables

Create a .env file in the root directory and add:

PORT=5000
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-secret-key>
REDIS_HOST=localhost
REDIS_PORT=6379

4️⃣ Start the Server

npm start

The server will run on http://127.0.0.1:5000/

