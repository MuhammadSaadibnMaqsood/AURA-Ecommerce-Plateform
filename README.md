# AURA Ecommerce Platform

AURA Ecommerce Platform is a full-stack **MERN (MongoDB, Express, React, Node.js)** based e-commerce application designed to demonstrate real-world software engineering practices.  
The project implements complete product management, secure authentication, image uploads, and QR-code-based warranty handling.

This project is built for **learning, portfolio demonstration, and practical full-stack development experience**.

---

## 🚀 Features

- User authentication using cookies & sessions  
- Product management (Create, Read, Update, Delete)  
- Secure image upload using **Multer + Cloudinary**  
- QR Code generation for product warranty/verification  
- RESTful API architecture  
- Separate frontend and backend codebases  
- Scalable and modular folder structure  

---

## 🛠️ Tech Stack

### Frontend
- React
- JavaScript (ES6+)
- CSS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (file uploads)
- Cloudinary (image storage)
- QR Code Generator
- Cookie-based Authentication

---

## 📁 Project Structure

AURA-Ecommerce-Plateform/
│
├── Backend/
│ ├── controllers/ # Business logic
│ ├── models/ # MongoDB schemas
│ ├── routes/ # API routes
│ ├── middleware/ # Authentication & helpers
│ ├── utils/ # QR code & utilities
│ ├── server.js # Backend entry point
│ └── package.json
│
├── Frontend/
│ ├── src/
│ │ ├── components/ # Reusable components
│ │ ├── pages/ # Application pages
│ │ ├── services/ # API calls
│ │ ├── App.js
│ │ └── index.js
│ └── package.json
│
├── .gitignore
└── README.md



---

## ⚙️ Getting Started

Follow the steps below to run the project locally.

---

## ✅ Prerequisites

Make sure you have installed:

- Node.js (v16 or higher)
- npm or yarn
- MongoDB (local or MongoDB Atlas)
- Cloudinary account

---

## 🔧 Backend Setup

1. Navigate to backend directory:

```bash

cd Backend


Install dependencies:


npm install


Create a .env file inside Backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
SESSION_SECRET=your_secret_key


npm run dev

cd Frontend

npm install

npm start



🔗 API Overview


Authentication

POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/logout
GET    /api/auth/me

Products

GET    /api/products
GET    /api/products/:id
POST   /api/products
PUT    /api/products/:id
DELETE /api/products/:id


Upload & QR

POST   /api/upload
GET    /api/qrcode/:productId


🧪 Purpose of the Project

Demonstrate full-stack MERN development

Practice backend API design

Implement file uploads and cloud storage

Understand real-world authentication flows

Use QR codes for business use-cases (warranty tracking)

👤 Author

Muhammad Saad ibn Maqsood
Software Engineering Undergraduate

