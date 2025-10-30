# 📸 Memories Project

A full-stack social media platform where users can create, view, and share memorable moments with others in real time. The project is designed with a focus on scalability, performance, and clean architecture using **React**, **Redux**, **Java**, **Spring Boot**, **Express**, **MongoDB**, and **Redis**.

---

## 🚀 Overview

The **Memories Project** allows users to post their memories with titles, descriptions, and photos, while securely managing authentication and data retrieval.  
The platform demonstrates full-stack development principles including RESTful API design, optimized database queries, and state management using Redux.

---

## ⚙️ Tech Stack

**Frontend**
- React.js (Hooks, reusable components)
- Redux (for global state management)
- HTML5, CSS3, JavaScript (ES6+)
- ngrok (for tunneling backend during development)

**Backend**
- Java & Spring Boot (RESTful APIs)
- Express.js (middleware routing and request handling)
- MongoDB (NoSQL database for scalable data storage)
- Redis (for caching and token management)
- Dispatcher (for event-driven updates)

---

## 💡 Key Features

- 🔐 **Secure Authentication** — Implemented token-based login and access control using Redis for managing sessions.  
- ⚡ **High Performance** — Optimized database queries through indexing, reducing latency by over **90%**.  
- 🧩 **Reusable UI Components** — Built modular React components and stateful Redux architecture for scalability.  
- 🌐 **RESTful API Design** — Developed backend APIs with proper HTTP verbs, status codes, and response structures.  
- 🗂️ **Data Persistence** — Leveraged MongoDB for dynamic data storage and retrieval.  
- 📡 **Seamless Local Development** — Used ngrok to expose local APIs securely during frontend integration.

---

## 🧠 Architecture

```plaintext
Frontend (React + Redux)
        ↓
 REST API Gateway (Express.js)
        ↓
 Backend Service (Spring Boot)
        ↓
 Database Layer (MongoDB + Redis)
