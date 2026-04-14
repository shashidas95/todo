
# 📝 MERN Stack Task Management System

A full-stack **Task Management Application** built using the **MERN** (MongoDB, Express, React, Node.js) architecture. This project serves as a comprehensive showcase of modern web development, featuring a decoupled frontend and backend for maximum scalability.

---

## 🏗️ System Architecture

The application is split into two primary layers, ensuring a clean separation of concerns:

- **Frontend (React)**: A highly interactive UI built with reusable components, state management, and real-time data fetching.
- **Backend (Node.js & Express)**: A robust RESTful API that handles business logic, user authentication, and database interactions.
- **Database (MongoDB)**: A flexible NoSQL database used to store user tasks with high availability.

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS (or CSS3), Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Security**: JWT-based Authentication
- **Environment**: Dotenv for secure variable management

---

## 🚀 Key Features

- **Full CRUD Functionality**: Create, read, update, and delete tasks with instant UI updates.
- **RESTful API Design**: Clean and documented endpoints for seamless frontend-backend communication.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop screens.
- **Secure Persistence**: User data is securely stored and retrieved using Mongoose models.

---

## 💻 Setup & Installation

### **Prerequisites**
- Node.js & NPM
- MongoDB (Local instance or Atlas URI)

### **Installation Steps**

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/shashidas95/todo.git](https://github.com/shashidas95/todo.git)
   cd todo
   ```

2. **Install Dependencies**:
   ```bash
   # Install for Backend
   npm install
   
   # Navigate to client and install for Frontend
   cd client && npm install
   ```

3. **Configure Environment**:
   Create a `.env` file in the root directory:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. **Run the Application**:
   ```bash
   # From the root directory (using concurrently)
   npm run dev
   ```

---

## 📂 Project Structure

- `/client`: React frontend source code and components.
- `/models`: Mongoose schemas for MongoDB data modeling.
- `/routes`: Express route definitions for API endpoints.
- `/controllers`: Logic for handling incoming requests and returning responses.

---

## 👨‍💻 Author
**Shashi Kanta Das**
*Software Architect | DevOps Engineer | Assistant Director @ BSTI*


How does your GitHub Profile look now? We have covered almost all your major repositories!
