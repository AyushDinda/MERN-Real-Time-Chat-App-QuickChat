# MERN-Real-Time-Chat-App-QuickChat
MERN Realtime Chat Application with Socket.io, JWT Authentication, Cloudinary image upload, and MongoDB. Supports real-time messaging, online status, and media sharing.

# 💬 MERN Realtime Chat App

A full-stack realtime chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.io for instant messaging. The app supports user authentication, online status tracking, image sharing via Cloudinary, and responsive UI.

## 🚀 Features

- 🔐 JWT Authentication (Signup/Login)
- 💬 Realtime messaging using Socket.io
- 🟢 Online/Offline user status
- 🖼️ Image sharing with Cloudinary
- 📩 Unseen message notifications
- 👤 User profile with avatar
- 📱 Responsive modern UI
- ⚡ Instant message delivery without refresh

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Context API
- Tailwind CSS
- Axios
- Socket.io Client

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- Cloudinary

## 📂 Project Structure

```
client/    → React frontend  
server/    → Node/Express backend  
```

## ⚙️ Environment Variables

Create a `.env` file in the server folder:

```
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx
```

## ▶️ Run Locally

### Backend

```
cd server
npm install
npm run dev
```

### Frontend

```
cd client
npm install
npm run dev
```

## 🌐 Deployment

- Frontend: Vercel
- Backend: Render / Railway
- Database: MongoDB Atlas
- Media Storage: Cloudinary

## 📸 Screenshots

(Add screenshots here)

## 📄 License

MIT License

---

⭐ If you like this project, give it a star!
