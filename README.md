# 💬 Real-Time Chat Application

A *full-stack real-time chat application* with secure authentication, instant messaging, and image sharing — built to demonstrate modern web development best practices.

---

## 🚀 Features

✨ *Real-Time Messaging*
- Instant one-to-one chat using WebSockets
- Live message delivery without page refresh

🔐 *Secure Authentication*
- JWT-based authentication
- Protected routes & secure session handling

🖼️ *Image Sharing*
- Upload and send images in chat
- Optimized and securely stored files

👤 *User Management*
- User signup & login
- Online/offline status tracking

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- WebSocket / Socket.io

### Database
- MongoDB

### Authentication & Security
- JSON Web Tokens (JWT)
- bcrypt for password hashing

### File Handling
- Cloudinary (for image uploads)

---

## 🧩 Architecture Overview

```text
Client (React)
   ↓  REST APIs / WebSockets
Server (Node + Express)
   ↓
MongoDB Database
