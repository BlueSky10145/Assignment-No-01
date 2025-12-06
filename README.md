# HalkaBite – AI-Powered Food Delivery Website

![MERN Stack](https://img.shields.io/badge/Stack-MERN-green)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue)
![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-cyan)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 Description

**HalkaBite** is an advanced online food delivery platform built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It connects customers with nearby restaurants and enhances the food ordering experience through **AI-powered automation** and multiple secure payment options.

---

## ✨ Features

### 🛒 User Features

| Feature | Description |
|---------|-------------|
| **Browse & Search** | Search food items by category or restaurant |
| **Cart & Orders** | Add items to cart, place orders easily |
| **Payments** | Bkash, Nagad, Rocket (via SSL Commerz) & COD |
| **AI Voice Ordering** | Order using voice commands |
| **Smart Menu** | Quickly reorder favorite meals |
| **Order History** | View history, manage profile, reorder |
| **Discounts** | Apply discount codes and view offers |
| **Reviews** | Rate and review dishes or restaurants |
| **Responsive** | Works on mobile and desktop |
| **Email Notifications** | Order confirmation emails |

### 🔧 Admin Features

| Feature | Description |
|---------|-------------|
| **Menu Management** | Add, edit, delete food items & categories |
| **Order Management** | Manage and update customer orders |
| **Analytics** | View sales analytics and metrics |
| **Promotions** | Manage coupons and offers |
| **Catering Agent** | Route orders to proper workflows |
| **Inventory** | Monitor stock and availability |
| **AI Chatbot** | 24/7 automated support |
| **Restaurant Info** | Manage menus and hours |

---

## 🛠️ Technology Stack

```
┌─────────────────────────────────────────────────────────────┐
│                        FRONTEND                             │
│  React.js (TypeScript) + TailwindCSS + Redux Toolkit        │
├─────────────────────────────────────────────────────────────┤
│                        BACKEND                              │
│  Node.js + Express.js (TypeScript) + Mongoose               │
├─────────────────────────────────────────────────────────────┤
│                       DATABASE                              │
│  MongoDB                                                    │
├─────────────────────────────────────────────────────────────┤
│                      INTEGRATIONS                           │
│  SSL Commerz | Google Gemini AI | NodeMailer                │
└─────────────────────────────────────────────────────────────┘
```

---

## 📁 Project Structure

```
HalkaBite/
├── frontend/                # React.js Frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Page components
│   │   ├── features/        # Redux slices
│   │   ├── services/        # RTK Query API
│   │   ├── hooks/           # Custom hooks
│   │   ├── utils/           # Utility functions
│   │   └── types/           # TypeScript types
│   └── ...
│
├── backend/                 # Node.js Backend
│   ├── src/
│   │   ├── controllers/     # Route controllers
│   │   ├── models/          # Mongoose models
│   │   ├── routes/          # Express routes
│   │   ├── middleware/      # Custom middleware
│   │   ├── services/        # Business logic
│   │   ├── utils/           # Utility functions
│   │   └── types/           # TypeScript types
│   └── ...
│
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- **Node.js** (v18 or higher)
- **MongoDB** (Local or Atlas)
- **npm** or **yarn**

### 🔧 Installation & Setup

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/halkabite.git
cd halkabite
```

#### 2. Backend Setup

Navigate to the backend directory, install dependencies, and configure environment variables.

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory based on `.env.example`:

```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Database
MONGODB_URI=mongodb://localhost:27017/halkabite

# JWT
JWT_SECRET=your_jwt_secret_key_here
JWT_EXPIRE=30d

# Client URL (for CORS)
CLIENT_URL=http://localhost:5173

# Google Gemini AI
GEMINI_API_KEY=your_gemini_api_key_here

# Email (Optional - for notifications)
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
```

Start the backend server:

```bash
npm run dev
```

#### 3. Frontend Setup

Open a new terminal, navigate to the frontend directory, and install dependencies.

```bash
cd frontend
npm install
```

Create a `.env` file in the `frontend` directory based on `.env.example`:

```env
VITE_API_URL=http://localhost:5000/api
```

Start the frontend development server:

```bash
npm run dev
```

The application should now be running at `http://localhost:5173`.

---

## 📡 API Documentation

The backend API is documented using **Postman**. You can import the provided collection to test the endpoints.

- **Base URL:** `http://localhost:5000/api`
- **Postman Collection:** `postman-collection.json` (located in root or backend folder)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🎯 Goal

To develop a reliable, intelligent, and user-friendly food delivery platform that:
- Improves customer experience
- Automates restaurant operations
- Ensures secure and seamless transactions

---

## 📊 Expected Outcomes

- ⚡ Faster food ordering experience
- 🤖 Reduced restaurant workload via AI automation
- 🎙️ Seamless voice and chatbot ordering
- 📈 Efficient order management and analytics
- 🔒 Secure payments with multiple gateways
- 💬 24/7 automated customer support
