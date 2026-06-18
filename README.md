# 🛒 Full Stack E-Commerce Project

A full-stack e-commerce web application built using **Spring Boot (Backend)**, **h2 Database Driver** and **React (Frontend)**.  
It supports product management, cart system, stock control, and image handling.

---

## 🚀 Features

### 👤 User Features
- View all products
- Filter by category
- View product details
- Add products to cart
- Increase / decrease quantity
- Checkout and update stock automatically

### 🛠 Admin Features (Basic)
- Add new product
- Update product
- Delete product
- Upload product image
- Manage stock quantity
- Mark product availability

---

## 🧠 Key Functionalities

- Stock-aware cart system (prevents over-ordering)
- Auto "Out of Stock" handling
- Image stored and served from backend
- Category-based filtering
- Persistent cart (frontend state)

---

## 🏗 Tech Stack

### Frontend
- React
- Axios
- React Router
- Bootstrap

### Backend
- Spring Boot
- Spring Data JPA
- REST APIs
- H2 Database

---

## 📦 Project Structure

ecom-project/
├── ecom-backend
├── ecom-frontend
└── imgs


---

## 🔗 API Endpoints (Sample)

- GET `/api/products` – Get all products
- GET `/api/product/{id}` – Get product by ID
- POST `/api/product` – Add product
- PUT `/api/product/{id}` – Update product
- DELETE `/api/product/{id}` – Delete product
- GET `/api/product/{id}/image` – Get product image

---

## ⚙️ How to Run Locally

### Backend
```bash
cd ecom-backend
mvn spring-boot:run

### Frontend
cd ecom-frontend
npm install
npm run dev


🎯 Future Improvements
JWT Authentication (Login/Register)
Admin dashboard
Order history
Wishlist feature
Payment integration (Stripe/Razorpay)
Deployment (Render + Vercel)


👨‍💻 Author

Harshal Gawali
Full Stack Developer (Learning Phase Project)
