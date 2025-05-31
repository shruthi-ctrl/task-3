# 📚 Books REST API with Node.js & Express

This is a simple *RESTful API* to manage a list of books using *Node.js* and *Express.js. The API supports basic CRUD operations (Create, Read, Update, Delete) and stores data **in-memory* (no database used).

## ✅ Features

- GET /books — Fetch all books
- POST /books — Add a new book
- PUT /books/:id — Update a book by ID
- DELETE /books/:id — Delete a book by ID

## 🛠 Tech Stack

- Node.js
- Express.js
- Postman (for testing)

## 📁 How to Run

1. *Initialize the project:*
   ```bash
   npm init -y

2. Install Express:

npm install express


3. Create your main file (e.g., index.js) and implement the server logic.


4. Run the server:

node index.js


5. Test your endpoints using Postman.



📌 Example Book Object

{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}

🚀 Outcome

Learned how to set up an Express server

Handled routing and HTTP methods (GET, POST, PUT, DELETE)

Managed in-memory JSON data
