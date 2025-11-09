# 🚀 Primetrade.ai Backend Developer (Intern) – Assignment

A full-stack web application demonstrating **secure, scalable REST APIs** with **JWT authentication**, **role-based access control**, and a simple **Vite + React frontend** for API interaction.

---

## 📋 Project Overview

This project fulfills the **Backend Developer (Intern) assignment** for **Primetrade.ai**.  
It includes:
- A **Node.js + Express + MongoDB backend**
- A **Vite-React frontend** for testing and interacting with the APIs

The goal is to demonstrate:
- Secure authentication and authorization
- CRUD operations
- Scalable architecture
- Frontend integration with protected routes

---

## 🏗️ Tech Stack

### **Backend**
- Node.js + Express.js
- MongoDB with Mongoose ORM
- JWT Authentication (Access & Refresh Tokens)
- Bcrypt.js for password hashing
- dotenv for environment variables
- CORS, Helmet, and Express Validator for security
- Postman for API documentation

### **Frontend**
- React (Vite)
- Axios for API requests
- React Router DOM for navigation
- Context API / LocalStorage for JWT handling
- TailwindCSS or CSS Modules for styling

---

## ⚙️ Features

### 🔐 Authentication & Authorization
- User registration and login with hashed passwords
- Role-based access control (`user`, `admin`)
- JWT-based authentication for protected routes

### 🧩 CRUD APIs
- Example entity: `Users`
- Create, Read, Update, Delete endpoints
- Accessible only to authorized users

### 💾 Database
- MongoDB schema design using Mongoose

### 🧱 API Versioning & Validation
- Organized routes with versioning
- Input validation using `express-validator`
- Centralized error handling

### 🧑‍💻 Frontend UI
- Register and login pages
- Protected dashboard after authentication
- CRUD interface for entity operations
- Display API success/error messages
