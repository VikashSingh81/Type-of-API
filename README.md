# Notes API (Node.js + Express)

A simple REST API built with **Node.js** and **Express** that allows users to create, read, update, and delete notes.

## 🚀 Features

* Create a new note
* Get all notes
* Update a note
* Delete a note
* Built using Express.js

## 📂 Project Structure

```
api-backend
│
├── src
│   └── app.js
├── server.js
├── package.json
├── package-lock.json
└── .gitignore
```

## ⚙️ Installation

Clone the repository and install dependencies.

```
git clone https://github.com/YOUR_USERNAME/notes-api.git
cd notes-api
npm install
```

## ▶️ Run the Server

```
node server.js
```

Server will start on:

```
http://localhost:3000
```

## 📌 API Endpoints

### 1️⃣ Create Note

POST `/notes`

Body:

```
{
"title": "Test Title",
"description": "Test Description"
}
```

---

### 2️⃣ Get All Notes

GET `/notes`

---

### 3️⃣ Update Note

PATCH `/notes/:index`

Example:

```
PATCH /notes/0
```

Body:

```
{
"description": "Updated description"
}
```

---

### 4️⃣ Delete Note

DELETE `/notes/:index`

Example:

```
DELETE /notes/0
```

---

## 🛠 Technologies Used

* Node.js
* Express.js
* Postman (API testing)

## 📬 Author

**Vikash Singh**

GitHub: https://github.com/VikashSingh81
