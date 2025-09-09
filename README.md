# 🍔 GrubHub — Food Ordering Platform

A full-stack food ordering platform built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) plus **Firebase** and **Tailwind CSS**.  
This project allows users to browse menus, place food orders, make secure payments, and track deliveries in real time. An **Admin Dashboard** is included for restaurant, menu, and order management.

---

## ✨ Features
- 🛒 **Food Ordering** — Browse restaurants and menus, add items to cart, update quantities, and place orders.
- 🔑 **Authentication** — Secure user login/registration with JWT & Firebase.
- 💳 **Payment Integration** — Integrated payment gateway for smooth transactions.
- 📦 **Order Tracking** — Real-time status updates for placed orders.
- 🛠 **Admin Dashboard** — Manage menu items, track orders, and oversee operations.
- 📱 **Responsive UI** — Built with React + Tailwind CSS for mobile-friendly performance.

---

## 🧱 Tech Stack
**Frontend:** React.js, Tailwind CSS, HTML, CSS, JavaScript  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Mongoose ODM)  
**Authentication:** Firebase Auth + JWT  
**Payments:** Payment Gateway API (Stripe/PayPal integration recommended)  
**Other Tools:** Redux, REST APIs, Git, Postman

---

## 🗂 Project Structure

```
GrubHub/
├── backend/     # Express server, routes, controllers, models
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── app.js
│   ├── .env.example
│   └── package.json
│
├── frontend/    # React client with Tailwind styling
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│   └── package.json
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/AdishPadalia26/GrubHub.git
cd GrubHub
```

### 2. Setup Backend
```bash
cd backend
cp .env.example .env   # add your MongoDB URI, Firebase keys, JWT secret, Payment API keys
npm install
npm run dev            # runs server on http://localhost:5000
```

### 3. Setup Frontend
```bash
cd frontend
npm install
npm start              # runs client on http://localhost:3000
```

---

### 🔐 Environment Variables (Backend)
Fill in `.env`:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret
FIREBASE_API_KEY=your_firebase_key
PAYMENT_API_KEY=your_payment_key   # e.g., Stripe or PayPal
```

---

### 🛠 API Endpoints (Sample)
```
GET    /api/restaurants
GET    /api/restaurants/:id/menu
POST   /api/cart
PATCH  /api/cart/:itemId
POST   /api/orders
GET    /api/orders/:orderId
```

---

## 📊 Roadmap

- Deploy backend (Render/Railway/Heroku)
- Deploy frontend (Vercel/Netlify)
- Add email notifications for order status
- Extend admin dashboard with analytics
- Support multiple restaurants & drivers

---

## 📄 License

MIT — free to use, modify, and extend.

---

## 👤 Author

Developed by **Adish Padalia**  
📧 padaliaadish@gmail.com  
🌐 [GitHub: AdishPadalia26](https://github.com/AdishPadalia26)  
🔗 [LinkedIn: adish-padalia-a3768a230](https://www.linkedin.com/in/adish-padalia-a3768a230/)

---
