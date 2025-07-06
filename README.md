Here's a polished and professional `README.md` for your **Fullstack Chat App**:

---

```markdown
# 💬 Fullstack Chat App

A powerful and modern real-time chat application built using the **MERN** stack with **Socket.io**, **TailwindCSS**, and **DaisyUI**.

---

## 🔧 Tech Stack

- ⚙️ **MERN** (MongoDB, Express.js, React.js, Node.js)
- 🔌 **Socket.io** – Real-time messaging
- 🎨 **TailwindCSS** + **DaisyUI** – Clean and responsive UI
- 🔐 **JWT** – Authentication & Authorization
- 📡 **Zustand** – Lightweight global state management
- ☁️ **Cloudinary** – Image storage
- 🛠️ Robust error handling (Client + Server)

---

## 📂 Project Structure

```

fullstack-chat-app/
├── backend/         # Node.js + Express + MongoDB + JWT + Socket.io
├── frontend/        # React + TailwindCSS 
└── README.md

````

---

## 🚀 Features

- 🎃 JWT-based **Authentication** and **Authorization**
- 👥 Real-time **chat messaging**
- 🟢 **Online user status** indicator
- 📸 **Cloud image uploads**
- 🔁 **Persistent state** with Zustand
- 💥 **Full error handling** (client & server)

---

## 🛠️ Setup

### 1. Clone the Repo

```bash
git clone https://github.com/Prateekrajput9/Chattingapp.git
cd fullstack-chat-app
````

### 2. Set up `.env` in `/backend` folder

```env
MONGODB_URI=your_mongo_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

---

## 🧱 Build the App

Build the frontend and install dependencies:

```bash
npm run build
```

This will:

* Install dependencies in `frontend` and `backend`
* Build the React frontend using Vite

---

## ▶️ Run the App

Start the backend (and serve the built frontend):

```bash
npm start
```

> 🟢 Your full app will run on: `http://localhost:5001`

---

### 🔄 For Development

Run backend and frontend separately:

```bash
# Terminal 1
backend:

npm run build 
npm start

# Terminal 2
cd frontend
npm install
npm run dev
```

---



## 📸 Screenshots

> *Add your app screenshots here!*

---

## 🧑‍💻 Author

Made with ❤️ by [Prateek Rajput](https://github.com/Prateekrajput9)


