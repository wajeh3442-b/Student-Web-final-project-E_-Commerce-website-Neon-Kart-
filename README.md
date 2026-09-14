# 🛒 E-Commerce React Application

## 📌 Project Overview

This project is a modern **E-Commerce Web Application** developed using React.js. It provides a complete shopping experience with authentication, product browsing, reviews, cart management, wishlist functionality, and notification messages.

The application uses React Context API to manage different parts of the application's state efficiently and make shared data available across components.

## ✨ Features

* 🔐 User Authentication
* 🛍️ Product Management
* ⭐ Product Reviews
* 🛒 Shopping Cart
* ❤️ Wishlist
* 🔔 Toast Notifications
* 🧭 React Router Navigation
* 📱 Responsive User Interface
* ⚡ Component-Based Architecture
* 🔄 Centralized State Management

## 🛠️ Technologies Used

* **React.js**
* **JavaScript (ES6+)**
* **React Router**
* **Context API**
* **HTML5**
* **CSS3**
* **Vite**

## 📂 Main Structure

```text
src/
│
├── components/
│   └── Toast/
│       └── ToastContext.jsx
│
├── context/
│   ├── AuthContext.jsx
│   ├── CartContext.jsx
│   ├── ProductContext.jsx
│   ├── WishlistContext.jsx
│   └── ReviewContext.jsx
│
├── App.jsx
├── index.css
└── main.jsx
```

## 🔄 Context Providers

### AuthProvider

Handles user authentication and authentication-related state.

### ProductProvider

Manages product information and product-related operations.

### ReviewProvider

Controls product reviews and review-related data.

### CartProvider

Manages shopping cart items and cart operations.

### WishlistProvider

Handles products added to the user's wishlist.

### ToastProvider

Displays notification messages such as success, error, and information alerts.

## 🚀 Installation

Clone or download the project and open it in VS Code.

Install the required dependencies:

```bash
npm install
```

## ▶️ Run the Project

Start the development server:

```bash
npm run dev
```

Vite will provide a local URL, usually:

```text
http://localhost:5173
```

Open the URL in your browser.

## 🧩 Application Architecture

The application uses nested Context Providers so that shared application data can be accessed by different components.

```text
BrowserRouter
    │
    └── ToastProvider
          │
          └── AuthProvider
                │
                └── ProductProvider
                      │
                      └── ReviewProvider
                            │
                            └── CartProvider
                                  │
                                  └── WishlistProvider
                                        │
                                        └── App
```

## 🎯 Purpose

The main purpose of this project is to demonstrate how React can be used to build a functional e-commerce application while maintaining clean component organization and centralized state management.

## 👨‍💻 Author

Developed as a React.js E-Commerce project for learning and academic purposes.

## 📄 License

This project is created for educational purposes.
