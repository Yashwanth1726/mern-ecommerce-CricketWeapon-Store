# 🏏 Cricket Weapon Store

A full-stack e-commerce web application for purchasing cricket equipment and accessories. This project is built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and provides a modern shopping experience with secure authentication, payment integration, and an admin dashboard.

---

## 🚀 Features

### 👤 User Features

- User Registration & Login (JWT Authentication)
- Forgot & Reset Password
- Browse Products
- Search & Filter Products
- Product Details
- Shopping Cart
- Wishlist
- Secure Checkout
- Stripe Payment Gateway
- Order History
- Product Reviews & Ratings
- User Profile Management
- Responsive UI

### 👨‍💼 Admin Features

- Admin Dashboard
- Manage Products
- Manage Users
- Manage Orders
- Manage Reviews
- Product Stock Management
- Sales Overview

---

## 🛠 Tech Stack

### Frontend

- React.js
- Redux
- Material UI
- Axios
- React Router

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Nodemailer
- Cloudinary
- Stripe API

---

## 📂 Project Structure

```
mern-ecommerce-CricketWeapon-Store
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── server.js
│
├── frontend
│   ├── public
│   ├── src
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Yashwanth1726/mern-ecommerce-CricketWeapon-Store.git
cd mern-ecommerce-CricketWeapon-Store
```

### Install Dependencies

```bash
npm install
cd frontend
npm install
cd ..
```

### Configure Environment Variables

Create a `.env` file inside the backend/config folder.

```env
PORT=5000
DB_LINK=YOUR_MONGODB_URI
JWT_SECRET=YOUR_SECRET
JWT_EXPIRE=5d

SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
SMTP_MAIL=YOUR_EMAIL
SMTP_PASS=YOUR_PASSWORD

CLOUDINARY_NAME=YOUR_NAME
API_KEY=YOUR_API_KEY
API_SECRET=YOUR_SECRET

STRIPE_API_KEY=YOUR_KEY
STRIPE_SECRET_KEY=YOUR_SECRET
```

---

## ▶️ Run the Project

### Backend

```bash
cd backend
npm start
```

### Frontend

```bash
cd frontend
npm start
```

---

## 📌 Future Improvements

- AI Product Recommendation
- Wishlist
- Coupon System
- Order Tracking
- Inventory Analytics
- Multi-language Support
- Dark Mode

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**Yashwanth**

GitHub: https://github.com/Yashwanth1726
