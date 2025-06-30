# 🛒 ProShop 2.0 – Full-Stack eCommerce App 🚀

![ProShop Banner](https://raw.githubusercontent.com/your-username/proshop2/main/public/banner.png)

> A complete **MERN stack eCommerce platform** with PayPal integration, JWT authentication, secure admin access, and powerful cart functionality. Built for scalability, real-world deployment, and great UX.

---

## 📦 Tech Stack

### 🧠 Frontend

* ⚛️ **React 18** + React Router DOM v6
* 🎨 **React Bootstrap** + **Bootstrap 5** for styling
* 💰 **PayPal JS SDK** via `@paypal/react-paypal-js`
* ⚙️ **Redux Toolkit** + React Redux for state management
* 🔔 **React Toastify** for notifications
* ⚙️ **React Helmet Async** for SEO management

### ⚙️ Backend

* 🌐 **Express.js** as the API framework
* 🔐 **JWT Authentication**
* 🍪 **cookie-parser** for cookie management
* 🔒 **bcryptjs** for password encryption
* 💾 **MongoDB** with **Mongoose**
* 📤 **Multer** for file uploads
* 🌿 **dotenv**, **colors** for environment & console enhancements

---

## 🚀 Features

### 👥 User

* Register/Login with JWT Auth
* Profile Management
* Add/Remove Cart Items
* Checkout with PayPal
* View Order History

### 📦 Product

* Browse products by category
* View single product details
* Rating & Review system

### 🛠️ Admin

* Full CRUD for Products/Users/Orders
* Manage Inventory & Pricing
* Upload Product Images
* Manage Order Status

---

## 📸 Screenshots

 ![Screen](https://github.com/asmit557/Shopping-Cart--Web-Application/blob/main/frontend/public/images/screens.png)

---

## 🛠️ Local Setup

### 🔃 Clone the Repository

```bash
git clone https://github.com/asmit557/Shopping-Cart--Web-Application.git
cd Shopping-Cart--Web-Application
```

### 📁 Backend Setup

```bash
npm install
cp .env.example .env  # Add Mongo URI, JWT secret, PayPal keys, etc.
npm run server
```

### 💻 Frontend Setup

```bash
cd frontend
npm install
npm start
```

### 🚀 Run Both (Dev)

```bash
npm run dev
```

> 💡 Dev server uses `concurrently` to run both frontend and backend.

---

## 📦 Seed Database

```bash
npm run data:import     # Import sample users/products
npm run data:destroy    # Delete all data
```

---

## 📚 Important Packages

| Package                    | Purpose                     |
| -------------------------- | --------------------------- |
| **axios**                  | API requests                |
| **redux toolkit**          | State management            |
| **react-bootstrap**        | UI components               |
| **jsonwebtoken**           | Secure auth tokens          |
| **bcryptjs**               | Password encryption         |
| **multer**                 | File uploads                |
| **paypal/react-paypal-js** | Payment gateway             |
| **nodemon**                | Hot reload for backend      |
| **concurrently**           | Parallel process management |

---

## 🌍 Environment Variables

Create a `.env` file in the root:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
```

---

## 📦 Build for Production

```bash
npm run build
```

> Builds frontend and prepares app for deployment.

---

## 🤝 Contribution Guide

* 🍴 Fork the repository
* 🛠️ Create your feature branch: `git checkout -b feature/YourFeature`
* ✅ Commit your changes: `git commit -m 'Add YourFeature'`
* 📤 Push to the branch: `git push origin feature/YourFeature`
* 🔃 Open a Pull Request

---

## 🌟 Show Your Support

If you like this project, consider giving it a ⭐ on GitHub!

[![GitHub stars](https://img.shields.io/github/stars/asmit557/Shopping-Cart--Web-Application?style=social)](https://github.com/asmit557/proshop2)

---

Made with ❤️ by [Asmit](https://github.com/asmit557)







