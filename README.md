# ToDo List Application with MERN Stack  

**A modern task management solution built using MongoDB, Express, React, and Node.js**  

This project provides a full-stack application for managing daily tasks with intuitive CRUD (Create, Read, Update, Delete) functionality. Designed for simplicity and efficiency, it empowers users to organize their workflow seamlessly.  

---

## ✨ Features  
- **Add tasks** with descriptive titles and optional details.  
- **Mark tasks as complete** with a single click to track progress.  
- **Edit existing tasks** to update descriptions or correct errors.  
- **Delete tasks** to remove unnecessary items.  
- **Responsive design** that adapts to desktop and mobile screens.  
- **Persistent storage** using MongoDB to retain tasks between sessions.  

---

## 🛠️ Tech Stack  
- **Frontend**:  
  - React.js (with functional components and hooks)  
  - HTML5/CSS3 (flexbox and grid layouts)  
- **Backend**:  
  - Node.js & Express.js (REST API development)  
  - MongoDB (NoSQL database for task storage)  
- **Tools**:  
  - Git (version control)  
  - Postman (API testing)  

---

## 🚀 Installation  
Follow these steps to run the project locally:  

### Prerequisites  
- Node.js v18+ and npm installed  
- MongoDB Atlas account or local MongoDB instance  

### Setup Instructions  
1. **Clone the repository**:  
```bash
git clone https://github.com/sruthivellore/ToDoList.git
cd ToDoList
```

2. **Configure the backend**:  
```bash
cd backend
npm install
# Create a .env file with your MongoDB URI:
echo "MONGODB_URI=your_connection_string" > .env
npm start
```

3. **Launch the frontend**:  
```bash
cd ../mern-todo-app
npm install
npm start
```

The backend will run at `http://localhost:5000`, and the frontend will open at `http://localhost:3000`.

---

**Happy task managing!** 🌟  

*(Replace "your_connection_string" with your actual MongoDB URI. For local MongoDB, use `mongodb://localhost:27017/todoapp`.)*  
