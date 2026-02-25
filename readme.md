# 🛒 Full-Stack E-commerce Platform

A comprehensive e-commerce platform developed as a collaborative academic project. The application features a client-server architecture, separating business logic and data persistence in the backend from the user interface.

The primary focus of this project was to implement core e-commerce mechanics, secure authentication, and relational database management.

## 🚀 Key Features

* **RESTful API:** Robust endpoints for managing products, user accounts, and order processing.
* **Authentication & Authorization:** Secure user login and registration using **JWT** (JSON Web Tokens) and Role-Based Access Control (RBAC) to differentiate between customers and administrators.
* **Relational Data Persistence:** Designed with SQL and **Sequelize ORM** to manage relational entities and guarantee transactional integrity during the checkout process.
* **Complex State Management:** Frontend built with **React** and **Context API** to handle global states like the shopping cart without prop-drilling.
* **Optimized Build:** Frontend bundled and served using **Vite** for fast hot-module replacement and optimized production builds.

## 🛠️ Tech Stack

**Backend:**
* Node.js
* Express.js
* SQL (via Sequelize ORM)
* JWT & bcrypt (Security)

**Frontend:**
* React.js
* Vite
* Context API

## ⚙️ Local Setup & Installation

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/m4lcom/node-express-ecommerce-api.git
```

### 2. Backend Configuration
```bash
cd backend
npm install
# Create a .env file based on environment requirements (e.g., DB credentials, JWT_SECRET)
npm run dev
```

### 3. Frontend Configuration
```bash
cd frontend
npm install
npm run dev
```

## 🧠 Architecture & Development Context

This repository was built simulating a real-world development workflow:
* **Separation of Concerns:** Distinct layers for routing, controllers, and database services.
* **Collaboration:** Version control and feature integration managed through Git workflows.
* *Note: As an academic prototype, certain production-level optimizations (e.g., pessimistic database locks, data-transfer objects for sensitive fields) are subject to future refactoring.*
