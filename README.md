# Full-Stack Web Application with MongoDB

## 📌 Project Overview
This project is a full-stack web application that allows users to register and store their information in a MongoDB database. The application demonstrates how a modern JavaScript stack connects a frontend interface to a backend server and persists data using a NoSQL database.

The project focuses on backend integration, database connectivity, and data persistence rather than complex UI design.

---

## 🛠️ Technologies Used
- **Node.js** – JavaScript runtime environment  
- **npm** – Package manager  
- **MongoDB** – NoSQL database for storing user data  
- **MongoDB Compass** – GUI tool for viewing and managing database data  
- **Express.js** – Backend framework  
- **Frontend Framework (React / Vite / Next.js)** – Runs in development mode using `npm run dev`  
- **Visual Studio Code** – Code editor  

---

## 📂 Project Structure

project-root/
│
├── src/ # Frontend source code
├── server/ or backend/ # Backend server and API logic
├── models/ # MongoDB schemas (Mongoose models)
├── routes/ # API route definitions
├── config/ # Database configuration
├── README.md # Project documentation
├── package.json # Dependencies and scripts
└── .env # Environment variables (MongoDB URI)


---

## 🗄️ Database
- The application uses **MongoDB** to store registered user data.
- Data is stored in **collections**, not tables (NoSQL).
- The MongoDB connection string is defined in an environment variable (`.env` file).

Example:

MONGODB_URI=mongodb://localhost:27017/projectDB

or

MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/projectDB


---

## 🔍 Viewing Stored Data
You can view registered user data using **MongoDB Compass**:

1. Open **MongoDB Compass**
2. Paste your MongoDB connection URI
3. Connect to the database
4. Select the database name
5. Open the relevant collection (e.g., `users`)
6. View documents created during registration

---

## ▶️ How to Run the Project

### 1️⃣ Install dependencies
```bash
npm install
2️⃣ Start the development server
npm run dev
3️⃣ Access the application

Open your browser

Navigate to the local URL shown in the terminal (commonly http://localhost:3000 or http://localhost:5173)

🧪 Features

User registration form

Backend API handling user data

MongoDB database connection

Persistent data storage

Data viewable through MongoDB Compass

📄 README Purpose

This README.md file serves as:

Project documentation

Setup guide

Explanation of data storage and architecture

Reference for instructors, recruiters, and collaborators

👤 Author
Oseme
Information Systems Graduate Student
Northeastern University

📌 Notes
This project is intended for educational purposes.
Sensitive files such as .env are not included in version control.
MongoDB Compass is used only for viewing and managing data, not for application logic
