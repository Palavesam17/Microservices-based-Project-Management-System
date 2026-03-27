# 🚀 Microservices-Based Project Management System

## 📌 Overview

This project is a **Microservices-Based Project Management System** designed to manage projects, tasks, and users efficiently in a scalable and distributed architecture.

Built using **Spring Boot, React.js, and REST APIs**, this system follows modern backend design principles with independent services and API communication.

---

## 🧩 Architecture

The application is built using **Microservices Architecture**, where each service is independently developed and deployed.

### 🔹 Key Microservices

* **User Service** – Handles user registration, authentication, and management
* **Project Service** – Manages project creation and details
* **Task Service** – Handles task assignment, tracking, and updates
* **API Gateway** – Routes requests to appropriate services
* **Service Registry (Eureka)** – Service discovery and registration
* **Config Server (Optional)** – Centralized configuration management

---

## 💻 Tech Stack

### 🔹 Backend

* Java
* Spring Boot
* Spring Cloud (Eureka, Gateway)
* RESTful APIs
* Microservices Architecture

### 🔹 Frontend

* React.js
* JavaScript
* HTML5, CSS3, Bootstrap

### 🔹 Database

* MySQL

### 🔹 Tools & Technologies

* Git & GitHub
* Maven
* Postman
* IntelliJ IDEA

---

## ⚙️ Features

* User Authentication & Authorization
* Project Creation & Management
* Task Assignment & Tracking
* REST API-based communication
* Scalable Microservices Design
* API Gateway for routing
* Service Discovery using Eureka

---

## 🔄 System Flow

1. User sends request via frontend (React.js)
2. Request goes through **API Gateway**
3. Gateway routes to appropriate microservice
4. Microservice processes request and interacts with database
5. Response is sent back to frontend

---

## 🛠️ Setup & Installation

### 🔹 Prerequisites

* Java 17+
* Maven
* Node.js & npm
* MySQL

### 🔹 Steps to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/project-management-system.git
```

2. Start services in order:

* Eureka Server
* API Gateway
* User Service
* Project Service
* Task Service

3. Setup frontend:

```bash
cd frontend
npm install
npm start
```

---

## 📡 API Testing

Use **Postman** to test APIs:

* User APIs
* Project APIs
* Task APIs

---

## 📈 Future Enhancements

* JWT Authentication & Security
* Role-Based Access Control (RBAC)
* Docker & Kubernetes Deployment
* CI/CD Pipeline Integration
* Notification Service (Email/SMS)

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

## 📬 Contact

**Palavesam**
📧 [palavesam624@gmail.com](mailto:palavesam624@gmail.com)
📞 +91 63828 35660

---

⭐ If you like this project, give it a star on GitHub!
