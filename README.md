# 📝 Task Manager API

A simple Task Manager API built using Node.js, Express, and MongoDB that supports full CRUD operations to manage tasks efficiently.

---

## 🚀 Features

* Create a new task
* Get all tasks
* Update a task
* Delete a task
* MongoDB database integration

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Testing/API Tool:** Postman

---

## ⚙️ Setup & Installation

### 1. Clone the repository

### 2. Install dependencies
  ```
  npm install
  ```

### 3. Setup environment variables
  Create a ```.env``` file in the root and add your MongoDB connection string:
  ```
  MONGO_URI=your_mongodb_connection_string
  PORT=5000
  ```
  Create a MongoDB account and connect your database to get the URI.

### 4. Run the server
  ```
  npm start
  ```

---

## 📌 API Endpoints (Basic)

* GET /api/tasks → Get all tasks
* POST /api/tasks → Create task
* PATCH /api/tasks/:id → Update task
* DELETE /api/tasks/:id → Delete task

---

## 📌 Note

Make sure MongoDB is properly connected using your ```.env``` file before running the project.


