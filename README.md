# LabAct2

# LabAct2 – Student & Course Management API

A simple RESTful API built with **Node.js**, **Express**, and **MySQL**.  
It provides CRUD operations for managing **Students** and **Courses**.

---

## Features
- Manage **Courses**
  - Create, Read, Update, Delete courses
- Manage **Students**
  - Create, Read, Update, Delete students
- MySQL database integration
- Organized routes & controllers
- CORS enabled
- `.env` support for sensitive configs

---

## Project Structure
.
├── controllers/ # Business logic for Students & Courses
├── routes/ # Express routes
├── config/ or db.js # Database connection
├── server.js # App entry point
├── package.json
└── README.md

---

## Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/madcitys/LabAct2.git
   cd LabAct2
2. **Install dependencies**
   npm install
3. **Set up environment variables**
    Create a .env file in the root directory:
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=yourpassword
    DB_NAME=labact2
    PORT=3000
5. **Run the server**
    npm start

**API Endpoints**
Courses

GET /api/courses – Get all courses
GET /api/courses/:id – Get a course by ID
POST /api/courses – Create a new course
PUT /api/courses/:id – Update a course
DELETE /api/courses/:id – Delete a course

Students

GET /api/students – Get all students
GET /api/students/:id – Get a student by ID
POST /api/students – Create a new student
PUT /api/students/:id – Update a student
DELETE /api/students/:id – Delete a student

**Tech Stack**

Node.js
Express
MySQL
dotenv
cors
