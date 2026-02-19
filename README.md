

# 🚀 SB Works – Freelancer Finder

**SmartInternz Full-Stack MERN Project**

SB Works – Freelancer Finder is a **professional full-stack web application** built using the **MERN stack** to connect **clients and freelancers** on a single platform.
The application enables **project posting, competitive bidding, role-based dashboards, and admin moderation**, ensuring a secure and scalable freelancing ecosystem.

> 📌 **Project Status:** In Development
> 🆔 **Team ID:** LTVIP2026TMIDS37879
> 🎓 **Program:** SmartInternz Group Project

---

## 🧩 Problem Statement

Finding reliable freelancers and managing projects efficiently is challenging due to scattered platforms, lack of transparency, and poor collaboration tools.

---

## 💡 Solution

SB Works provides a **centralized freelancer marketplace** where:

* Clients can post projects and manage bids
* Freelancers can browse jobs and submit proposals
* Admins ensure platform quality and security

---

## 🛠️ Tech Stack

### 🔹 Frontend

* React.js
* Bootstrap
* Material UI
* Axios

### 🔹 Backend

* Node.js
* Express.js

### 🔹 Database

* MongoDB
* Mongoose

### 🔹 Authentication & Security

* JWT (JSON Web Tokens)
* bcrypt.js

### 🔹 Developer Tools

* Postman
* MongoDB Compass
* VS Code

---

## ⚙️ Key Features

### 🔐 Secure Authentication

* Role-based access: **Client, Freelancer, Admin**
* JWT-protected APIs
* Password encryption using bcrypt

### 📌 Project Management

* Clients can post, update, and manage projects
* Freelancers can view active projects and place bids

### 📊 Dynamic Dashboards

* Personalized dashboards for each role
* Track bids, projects, and user profiles

### 🛡️ Admin Panel

* User moderation
* Project monitoring
* Platform integrity controls

### 🔄 REST API Integration

* Real-time data handling
* Clean and scalable backend architecture

---

## 👨‍💻 Project Team

### 👑 Team Leader

**Ghanta Sai Babu**
*Backend Architecture & Full-Stack Integration*

### 👥 Team Members

* **Kowthavarapu Kesav** – Frontend Development & UI/UX
* **Pathan Rasool Meharaj Khan** – API Development & Database Design
* **V Harshitha** – Testing, Documentation & Quality Assurance

---

## 📦 Getting Started

### ✅ Prerequisites

* Node.js (v16 or higher)
* MongoDB (Local or Atlas)
* Git

---

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/GhantaSaiBabu/freelancer_finder.git
cd freelancer_finder
```

#### Backend Setup

```bash
cd server
npm install
```

#### Frontend Setup

```bash
cd ../client
npm install
```

---

### ⚙️ Environment Configuration

Create a `.env` file inside the `/server` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

---

### ▶️ Run the Application

```bash
# Start Backend Server
cd server
npm start

# Start Frontend Client
cd ../client
npm start
```

🌐 Open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 📌 API Overview

| Method | Endpoint             | Description                      |
| ------ | -------------------- | -------------------------------- |
| POST   | `/api/auth/register` | User Registration                |
| POST   | `/api/auth/login`    | User Authentication              |
| GET    | `/api/projects`      | Fetch all projects               |
| POST   | `/api/projects`      | Post a new project (Client only) |
| POST   | `/api/bids`          | Submit a bid                     |

---

## 📂 Project Resources

* 📄 **Documentation & Demo:** Google Drive Folder
* 🎥 **Live Preview:** Recorded Demo Video

---

## 🔮 Future Enhancements

* 💬 Real-time Chat using Socket.io
* 💳 Payment Integration (Stripe / Razorpay)
* ⭐ Freelancer Rating & Review System
* 📱 Mobile App using React Native

---

## 📜 License

This project is developed for **educational purposes** under the SmartInternz program.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to fork the repository and submit a pull request.
