# 🖥️ Habit-Flow Server

## 📌 Overview

The **Habit-Flow-server** is the back-end application responsible for handling business logic, validation, and database operations.

---

## 🧠 Architecture

![System Architecture](https://github.com/user-attachments/assets/7d0b18a8-63e9-4f51-8763-7b27142b9a80)

### 🔎 Explanation

* **Client** → Sends requests
* **Server** → Processes logic
* **Database** → Stores data

👉 Flow: Client → Server → Database

---

## 🎯 Purpose

* Process client requests
* Validate data
* Manage habits (CRUD)
* Connect to the database

---

## ⚙️ Features

* Create Habit
* Get Habits
* Update Habit
* Delete Habit
* Mark Habit as Completed

---

## 🔗 API Endpoints

```
GET     /habits
POST    /habits
PUT     /habits/:id
DELETE  /habits/:id
PATCH   /habits/:id/done
```

---

## 🗂️ Project Structure

```
Habit-Flow-server/
│
├── src/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   ├── routes/
│   └── middlewares/
│
├── database/
└── package.json
```

---

## 🧩 Data Model

```
Habit {
  id: string
  title: string
  completed: boolean
  streak: number
}
```

---

## 🚀 Technologies

* Node.js
* Express.js
* TypeScript
* MongoDB / PostgreSQL

---

## 🔐 Security

* JWT Authentication
* Input validation
* Protected routes

---

## ✅ Conclusion

This is the core layer responsible for logic and data processing.
