# 🎥 MERN Stack Video Calling & Realtime Chat App

A full-stack video calling and real-time chat application built with the MERN stack (MongoDB, Express.js, React, Node.js). Features include one-on-one video calls, instant messaging, user authentication, and responsive design.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![MERN](https://img.shields.io/badge/stack-MERN-green.svg)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)

## ✨ Features

- 📹 **Real-time Video Calling** - High-quality peer-to-peer video calls using WebRTC
- 💬 **Instant Messaging** - Real-time text chat with Socket.IO
- 🔐 **Secure Authentication** - JWT-based user authentication with bcrypt password hashing
- 🎨 **Modern UI/UX** - Responsive design using Tailwind CSS
- 🖼️ **Image Uploads** - Cloud integration for profile pictures and media sharing
- 📱 **Mobile Responsive** - Works seamlessly on desktop and mobile devices
- 🟢 **Online Status** - See when users are online/offline
- 🔔 **Call Notifications** - Incoming call alerts and notifications

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Socket.IO Client
- Zustand (State Management)
- Simple-Peer (WebRTC wrapper)

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- Socket.IO
- JWT Authentication
- Cloudinary (Image Storage)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account or local MongoDB installation
- Cloudinary account (for image uploads)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mern-video-chat-app.git
   cd mern-video-chat-app
2.**Install server dependencies**
  cd server
  npm install
3.**Install client dependencies**
  cd ../client
  npm install
4.**Environment Variables**
 PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
Create a .env file in the client directory:
REACT_APP_SERVER_URL=http://localhost:5000
5.**Run the application**
  Start the server (from server directory):
  npm run dev
  Start the client (from client directory):
6. **npm start**
  Open the app
  Navigate to http://localhost:3000
🎯 **Usage**
Register/Login - Create an account or sign in with existing credentials
Dashboard - View list of online users
Start Chat - Click on a user to open chat window
Video Call - Click the video icon to initiate a video call
Accept/Decline - Incoming calls show notification with options
Media Sharing - Send images in chat using the attachment button
🖼️ **Screenshots**
Add screenshots of your application here
screenshots/login.png
screenshots/chat.png
screenshots/video-call.png
🙏 **Acknowledgments**
Socket.IO for real-time communication
WebRTC for peer-to-peer video calling
Simple-Peer for WebRTC abstraction
Tailwind CSS for styling
Cloudinary for image management
