# 🍽️ CT313H: Web Technologies and Services

> A modern, responsive, and user-friendly platform for **online food ordering** and **table reservations**.

## 📌 **Savorly** – Restaurant Ordering & Reservation Website

**Semester**: 1  
**Academic Year**: 2024–2025  

### 👩‍🎓 Contributor:
- **Nguyễn Thị Hoài Thương** – Developed and managed the admin-side functionality.
- **Ngô Thụy Thanh Tâm** – Responsible for the user interface and front-end logic.

**Class Number**: M03

---

## 🧾 Overview

The **Savorly Restaurant Ordering & Reservation Website** is a web application that allows users to browse food menus, place online orders, and book table reservations at restaurants. It supports two key user roles:
### 👤 Customer:
Can sign up, log in, browse menus, order food, and reserve tables.

### 🛠️ Admin:
Can manage menu items, view and process orders, and handle reservations.

---

## 📺 Demo

👉 [Savorly Restaurant Demo](https://youtu.be/qkObzXKYE5U?si=X1-iY0xWvVLvvhAL)

---

## 💻 Key Features

- 🧾 **Food Ordering:** browse menu, add to cart, place orders.
- 📅 **Table Reservation:** book tables with custom time slots
- 👤 **Table Reservation:** register, login, role-based access (user/admin)
- 🧑‍🍳 **Admin:** manage menu items, orders, and bookings
- 🔄 **RESTful API:** interaction between frontend and backend
## 🚀 How to Run the Project

### 1. Clone repository

```bash
git clone https://github.com/AlbusRosie/Savorly-Restaurant.git
cd Savorly-Restaurant
```

### 2. Setup Backend

```bash
cd backend-api
npm install
```

Create a `.env` file and configure your database connection:
```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=savorly_db
JWT_SECRET=your_jwt_secret
```

Run the backend server:
```bash
npm start
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

Open the app at http://localhost:5173

---

## 📄 Documentation

📌 For logic diagrams, database schema, and detailed flow – refer to: **ProjectReport_B2111949_B2111959.pdf**

---

## 📬 Contact

For feedback or questions, please reach out via GitHub or Gmail.

> ✨ *This project is for educational purposes only.*
