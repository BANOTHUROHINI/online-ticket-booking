# Ticket

## Online Ticket Booking Platform (Full Stack)

---

## 📌 Project Description

**Ticket** is a production-grade **full-stack online ticket booking platform** designed and developed using the **MERN stack**. The application enables end-to-end ticket discovery, booking, payment processing, and management for multiple travel modes including **Bus, Train, Launch, and Air**.

The system is architected with a **backend-first mindset**, focusing on clean REST APIs, secure authentication, role-based authorization, and scalable data handling. It simulates real-world business workflows commonly expected in **SDE-1 and Full-Stack engineering roles**.

---

## 🎯 Core Engineering Goals

* Design scalable and maintainable backend services
* Implement secure authentication and authorization flows
* Build RESTful APIs following industry standards
* Handle real-time booking and payment workflows
* Develop modular, reusable frontend components

---

## 👥 User Roles & Responsibilities

### 👤 User

* Account creation and secure login using Firebase Authentication
* Browse, search, and filter tickets by route, date, and price
* Complete bookings using integrated Stripe payment gateway
* View booking history and transaction details
* Fully responsive user interface

### 🧑‍💼 Vendor

* Vendor authentication with restricted access controls
* Create, update, and manage ticket listings
* View sales data and booking statistics
* Dedicated vendor dashboard

### 🛡 Admin

* Platform-level authentication and authorization
* Manage users and vendors
* Approve, suspend, or block vendors
* Monitor bookings, revenue, and system activity

---

## 🛠 Technology Stack

### Frontend

* **React 19** – Component-based UI development
* **React Router** – Client-side routing
* **Tailwind CSS** – Responsive UI styling
* **TanStack React Query** – Server state management
* **Firebase Auth** – Authentication
* **Stripe** – Payment processing
* **Recharts** – Dashboard analytics
* **Framer Motion** – UI animations

### Backend

* **Node.js** – Server runtime
* **Express.js** – REST API framework
* **MongoDB** – NoSQL database
* **JWT** – Secure route protection
* **Firebase Admin SDK** – Token verification
* **Stripe API** – Payment integration

---

## 🔐 Security & Authorization

* Firebase-based authentication flow
* JWT-protected API routes
* Role-based access control for User, Vendor, and Admin
* Secure handling of environment variables

---

## 💳 Payment & Booking Flow

* Secure Stripe checkout integration
* Server-side payment verification
* Persistent booking and transaction records
* Error handling for failed or duplicate payments

---

## 📊 Dashboards & Analytics

* Ticket sales and booking metrics
* Revenue tracking
* User and vendor activity insights
* Interactive charts for data visualization

---

## 🧱 Project Architecture

```
Client (React)
├── components
├── pages
├── routes
├── hooks
├── context
└── ui

Server (Node + Express)
├── routes
├── controllers
├── middleware
├── models
└── utils
```

---

## ⚙️ Local Setup

### Client

```bash
git clone <client-repository-url>
cd ticket-client
npm install
npm run dev
```

### Server

```bash
git clone <server-repository-url>
cd ticket-server
npm install
npm start
```

> Configure `.env` files for Firebase, MongoDB, JWT, and Stripe credentials.

---

## 🚀 Future Improvements

* Seat selection and availability mapping
* Ticket cancellation and refund workflows
* Email notifications and booking confirmations
* Multi-language support
* Native mobile application

---

⭐ Built to demonstrate real-world **backend logic, API design, authentication, and full-stack engineering skills** expected from an SDE-1 developer.
