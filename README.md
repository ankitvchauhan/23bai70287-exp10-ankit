# Experiment 10: CRUD Operations using Node.js + Express.js

## 📌 Objective

To implement CRUD (Create, Read, Update, Delete) operations on a database using Node.js and Express.js as backend and MongoDB as the database.

---

## Submission Details :

* Student - Ankit
* UID - 23BAI70287
* section - 23AML7-A
* Experiment - 10

---

## 🛠️ Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* Postman

---

## 📁 Project Structure

```
experiment10/
│
├── server.js
├── models/
│   └── Student.js
├── routes/
│   └── studentRoutes.js
├── package.json
```

---

## ⚙️ Installation & Setup

1. Initialize project:

```
npm init -y
```

2. Install dependencies:

```
npm install express mongoose cors
npm install --save-dev nodemon
```

3. Run the server:

```
npm start
```

4. Server runs on:

```
http://localhost:5000
```

---

## 🔌 Database Connection

MongoDB is connected locally using:

```
mongodb://127.0.0.1:27017/collegeDB
```

---

## 🔄 CRUD Operations

### 1️⃣ Create (POST)

* Endpoint: `/api/students`
* Description: Adds a new student record
* Sample Input:

```
{
  "name": "Rahul",
  "email": "rahul123@gmail.com",
  "course": "BCA"
}
```

---

### 2️⃣ Read (GET)

* Endpoint: `/api/students`

* Description: Fetch all student records

* Endpoint: `/api/students/:id`

* Description: Fetch single student record by ID

---

### 3️⃣ Update (PUT)

* Endpoint: `/api/students/:id`
* Description: Update student details
* Uses `{ new: true }` to return updated data

---

### 4️⃣ Delete (DELETE)

* Endpoint: `/api/students/:id`
* Description: Delete a student record

---

## 🧪 API Testing

All APIs were tested using Postman.

---

## 📸 Output

The following outputs were captured:

* Server running and database connection
* Create record success
* Read records
* Update record success
* Delete record success
* MongoDB Compass collection view

---

## 🎯 Conclusion

CRUD operations were successfully implemented using Node.js, Express.js, and MongoDB. The backend APIs were tested and verified using Postman, and data was stored and managed using MongoDB.

---
