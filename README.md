# 📚 Books CRUD API (Node.js + Express)

This is a simple RESTful API built using **Node.js** and **Express.js** that allows you to perform **CRUD (Create, Read, Update, Delete)** operations on books.  
The books are stored **in-memory** (no database used), making this ideal for learning or prototyping.

---

## 🚀 Features

- Create a new book
- Get all books
- Get a single book by ID
- Update a book by ID
- Delete a book by ID

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**

---

## 📁 Project Structure

```
books-api/
├── index.js       # Main server file with all routes
├── package.json    # Node project config file
└── README.md       # Documentation
```

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/karanprajapat824/books_management_backend.git
cd books_management_backend
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the server**

```bash
node index.js
```

> The server will start on: `http://localhost:3000`

---

## 📬 API Endpoints

### ➕ Create a Book

- **URL:** `POST /books`
- **Body:**
```json
{
  "title": "Book Title",
  "author": "Author Name"
}
```
- **Response:** `201 Created`

---

### 📚 Get All Books

- **URL:** `GET /books`
- **Response:** `200 OK`

---

### 📖 Get a Book by ID

- **URL:** `GET /books/:id`
- **Response:** `200 OK` or `404 Not Found`

---

### ✏️ Update a Book

- **URL:** `PUT /books/:id`
- **Body:** (You can update title, author or both)
```json
{
  "title": "Updated Title",
  "author": "Updated Author"
}
```
- **Response:** `200 OK` or `404 Not Found`

---

### ❌ Delete a Book

- **URL:** `DELETE /books/:id`
- **Response:** `200 OK` or `404 Not Found`

---

## ✅ License

This project is open-source and free to use.

---

## 🙋‍♂️ Author

Made with ❤️ by **Karan Prajapat**
GitHub: [karanprajapat824](https://github.com/karanprajapat824)
