🚀 Creative README (Books API)
# 📚 Books REST API

A simple and powerful REST API built with Node.js and Express.js to manage a collection of books.  
This project demonstrates how backend systems handle data using CRUD operations without a database.

---

## ✨ What This Project Does

This API allows users to:

- 📖 View all books  
- ➕ Add new books  
- ✏️ Update existing books  
- ❌ Delete books  

All operations are handled in real-time using in-memory storage.

---

## ⚙️ Tech Stack

- 🟢 Node.js — Backend runtime  
- 🚀 Express.js — Server & routing  
- 📦 JSON — Data format  

---

## 🔗 API Endpoints

| Method | Endpoint        | Description              |
|--------|---------------|--------------------------|
| GET    | /books        | Get all books            |
| POST   | /books        | Add a new book           |
| PUT    | /books/:id    | Update book by ID        |
| DELETE | /books/:id    | Delete book by ID        |

---

## 🧠 How It Works

1. The server runs on **port 3000**
2. Data is stored in a simple array (no database)
3. Each request is handled using Express routes
4. Responses are sent in JSON format

---

## ▶️ Getting Started

### 1️⃣ Install dependencies

### 2️⃣ Run the server

### 3️⃣ Open in browser or Postman
--->  http://localhost:3000/books


---

## 🧪 Testing the API

Use Postman to test:

### ➕ Add Book (POST)
```json
{
  "title": "New Book",
  "author": "Your Name"
}

⚠️ Important Notes
📌 Data is stored in memory → resets on server restart
📌 No database is used (for learning purpose)
💡 What I Learned
REST API fundamentals
Express routing and middleware
Handling HTTP methods
Working with JSON data
Building backend logic
👨‍💻 Author

Harsh walia


