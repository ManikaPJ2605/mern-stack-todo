✅ MERN Stack To-Do App

This is a simple **To-Do List application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
It allows users to **add**, **view**, **edit**, and **delete tasks** in an organized and responsive interface.

---

📁 Project Folder Structure

```

mern-stack-todo/
├── frontend/               # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       │   └── Todo.jsx
│       ├── App.js
│       └── index.js
│
└── todo-backend/           # Node.js + Express backend
├── models/
│   └── Todo.js
├── routes/
│   └── todoRoutes.js
├── .env                # MongoDB connection string
└── server.js

````

---

 🛠 Technologies Used

**Frontend:**
- React.js (Create React App)
- Axios (for API calls)
- CSS

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv, CORS

---

## 🔧 How to Run the Project Locally

### 1. 🚀 Clone the Repository

```bash
git clone https://github.com/ManikaPJ2605/mern-stack-todo.git
cd mern-stack-todo
````

---

### 2. ⚙️ Backend Setup

```bash
cd todo-backend
npm install
```

✅ Create a `.env` file inside the `todo-backend` folder with the following content:

```
MONGO_URL=your_mongodb_connection_string
PORT=5000
```

Start the backend server:

```bash
npm start
```

📍 Backend will run at: `http://localhost:5000`

---

### 3. 🎨 Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

📍 Frontend will run at: `http://localhost:3000`

Make sure your frontend connects to the backend on port `5000`.

---

## ✅ Features

* Add new tasks
* View all tasks
* Mark tasks as completed
* Edit task titles
* Delete tasks
* Fully connected with MongoDB (CRUD operations)

---

## 🙋‍♀️ Author

* **Manika P J**
* GitHub: [ManikaPJ2605](https://github.com/ManikaPJ2605)


