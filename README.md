
# 🛒 Full-Stack E-commerce Platform (MERN Stack)

A fully functional, modern e-commerce application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project demonstrates a clean architecture, secure authentication, product and cart management, and a responsive UI – all essentials for scalable, production-ready applications.

---

## 📌 Project Highlights

- 💡 **End-to-End Full Stack**: Seamless integration between frontend (React) and backend (Node/Express)
- 📦 **Product Catalog**: Dynamic product listings with details and categories
- 🛍️ **Shopping Cart**: Intuitive cart interface with real-time price calculations
- 🔐 **Authentication**: Secure user registration, login, and role-based access using JWT
- ⚙️ **REST API**: Modular and scalable backend with protected routes
- 💅 **Responsive UI**: Clean, mobile-friendly design with modern CSS
- 🧪 **Developer-Ready**: Easy to set up and extend – great for contributors and portfolio display

---

## 📁 Folder Structure

```text
Ecommerce-mern-demo/
├── backend/                # Express server, MongoDB models, routes, controllers
│   ├── controllers/        # Business logic
│   ├── models/             # Mongoose data models
│   ├── routes/             # API endpoints
│   ├── config/             # Database and env config
│   └── server.js           # Entry point for backend
│
├── frontend/               # React client-side application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── App.js          # Root React component
│   │   └── index.js        # ReactDOM entry point
│
├── .gitignore
├── README.md
├── package.json
├── package-lock.json
````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sohamd58/Ecommerce-mern-demo.git
cd Ecommerce-mern-demo
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Environment Variables

Create a `.env` file inside `backend/` and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the Application

Run both backend and frontend in two terminals:

```bash
# Terminal 1: Backend
cd backend
npm run dev
```

```bash
# Terminal 2: Frontend
cd frontend
npm start
```

---

## 🧩 Tech Stack

* **Frontend**: React, React Router, Context API
* **Backend**: Express.js, Node.js, MongoDB, Mongoose
* **Authentication**: JWT-based auth and protected routes
* **Tools**: dotenv, nodemon, concurrently, bcryptjs, axios

---

## 📣 Contributing

Pull requests are welcome! If you find a bug or have a suggestion, feel free to open an issue or submit a PR.

---

⭐ **Star this repo** to support the project!
📫 **Connect** via [LinkedIn](https://www.linkedin.com/in/soham-d1758) or GitHub!

---
