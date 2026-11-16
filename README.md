# MERN Notes App 📒

A **beginner-friendly full-stack project** built with the **MERN Stack (MongoDB, Express, React, Node.js)** using **TypeScript** and **Redux Toolkit**.  
Learn how frontend and backend connect in a real-world app while keeping the code simple, structured, and easy to understand.

---

## 🌟 Features

- 🧠 Beginner-friendly structure with clean folder organization
- ✨ Built completely with TypeScript (frontend + backend)
- 🧱 3-tier architecture (Routes → Controllers → Services → Repositories)
- 📝 Create, Read, and Delete Notes
- 🔄 Frontend–Backend communication via REST APIs
- ⚙️ Uses Redux Toolkit for state management

---

## 🧩 Tech Stack

| Layer               | Technology                         |
| ------------------- | ---------------------------------- |
| **Frontend**        | React + TypeScript + Redux Toolkit |
| **Backend**         | Express + Node.js (TypeScript)     |
| **Database**        | MongoDB (Mongoose ORM)             |
| **Runtime**         | Node.js                            |
| **Package Manager** | npm                                |

---

## 📁 Project Structure

mern-notes-app/

├── backend/ → Express + MongoDB (TypeScript)

└── frontend/ → React + Redux (TypeScript)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/mern-notes-app.git
cd mern-notes-app
```

### 2️⃣ Setup the backend

```bash
cd backend
npm install
npm run dev
```

Create a .env file

```bash
PORT=5000
NODE_ENV=development
MONGO_URI=mongodb://localhost:27017/mern_notes_app
```

### 3️⃣ Start the backend

```bash
npm run dev
```

The server should start on http://localhost:5000
You can test it by visiting:

```bash
GET http://localhost:5000/api/health
```

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

The app will start on http://localhost:3000
Vite’s proxy setup will forward /api calls to your backend.

### 💡 Learning Outcomes

- By completing this project, you’ll learn:
- How a frontend and backend communicate through REST APIs.
- How to use Redux Toolkit to manage global state.
- How to structure an Express app using a 3-tier architecture.
- How to use TypeScript effectively on both ends.
- How to connect Node.js with MongoDB using Mongoose.

### 🧰 Tools & Dependencies

#### Backend

- express
- mongoose
- dotenv
- cors
- typescript
- ts-node-dev

#### Frontend

- react
- vite
- redux toolkit
- react-redux
- axios
- typescript

## 🧑‍💻 Author

### Aditya Jadhav

- 📧 shukan.prajapati@appaspect.com
- 💼 GitHub: https://github.com/shukanprajapati-cyber
