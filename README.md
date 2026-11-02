<div align="center">

# 🛍️ SHYNEX
### *Redefining the Digital Fashion Experience*

[![React](https://img.shields.io/badge/Frontend-React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Node](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Firebase](https://img.shields.io/badge/Auth-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Redux](https://img.shields.io/badge/State-Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)

<br />

> **"Where Premium Fashion Meets Modern Technology."**

[🌐 Live Demo](https://shynex-6ejo.vercel.app) · [🐞 Report Issue](https://github.com/pushpender1043/Shynex_EcommerceStore/issues) · [📦 Request Feature](https://github.com/pushpender1043/Shynex_EcommerceStore/issues)

</div>

---

## 🎩 Introduction

**Shynex** is not just an e-commerce store; it's a full-stack D2C (Direct-to-Consumer) fashion platform designed for scalability and performance. Built on the robust **MERN Stack**, it features secure authentication via **Firebase**, global state management with **Redux**, and a seamless checkout experience.

Designed for the modern user who values speed, aesthetics, and security.

## ✨ Key Features

| Category | Features |
| :--- | :--- |
| **🛍️ Shopping Exp** | Interactive Product Cards, Dynamic Filters, Wishlist & Cart Management. |
| **🔐 Security** | **Firebase Auth** integration for secure Google/Email login. |
| **⚡ Performance** | Optimized backend with **Node.js & Express**, fast data retrieval from **MongoDB**. |
| **🧠 State Mgmt** | Complex state handling (Cart, User, Products) using **Redux Toolkit**. |
| **🎨 UI/UX** | Responsive design that looks premium on Mobile, Tablet, and Desktop. |
| **👨‍💻 Admin Panel** | Dedicated dashboard to manage products, inventory, and user orders. |

## 🛠️ The Tech Stack

Shynex is powered by the industry-standard **MERN** architecture:

- **Frontend & Admin:** `React.js` + `Vite`
- **Styling:** `Tailwind CSS` / `CSS3`
- **State Management:** `Redux Toolkit`
- **Backend:** `Node.js` + `Express.js`
- **Database:** `MongoDB`
- **Authentication:** `Firebase`

## 📂 Architecture

```text
Shynex_EcommerceStore/
├── frontend/               # Customer-facing React Application
│   ├── src/
│   │   ├── components/     # Reusable UI elements
│   │   ├── pages/          # Home, Shop, Cart, Checkout
│   │   └── redux/          # State slices and store
├── admin_panel/            # Admin Dashboard (React)
│   ├── src/
│   │   ├── components/     # Dashboard UI, Sidebar, Nav
│   │   └── pages/          # Add Products, Orders, Lists
└── backend/                # Node.js / Express Server
    ├── config/             # DB & Cloudinary configs
    ├── controller/         # Auth, Cart, Order, Product logic
    ├── model/              # MongoDB Schemas
    └── middleware/         # Auth verification, Multer
