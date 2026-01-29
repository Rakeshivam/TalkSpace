# 🚀 TalkSpace
### Real-Time Chat, Video Conferencing & Screen Sharing Platform

**TalkSpace** is a full-stack real-time communication platform that enables **instant messaging, video conferencing, audio calling, and live screen sharing**.  
It is built using modern web technologies to deliver **low-latency, secure, and seamless real-time communication**.

This project demonstrates real-world implementation of **WebRTC**, **Socket.io**, and **scalable full-stack architecture**, making it suitable for **learning, final-year projects, and production-ready systems**.

---

## ✨ Highlights

- 💬 Real-time chat
- 🎥 Video & audio calling
- 🖥 Live screen sharing
- ⚡ Low-latency communication
- 🔐 Secure authentication
- 📱 Fully responsive UI

---

## 🧠 Overview

Modern applications demand more than simple text-based messaging. Users expect **real-time interaction, collaboration, and seamless communication**.

TalkSpace brings everything together in one platform:
- Chat without page refresh
- Video meetings using peer-to-peer connections
- Screen sharing for collaboration
- Clean and modern user experience

---

## ❓ Problem Statement

Traditional communication systems often suffer from:
- High latency
- No real-time updates
- Dependency on multiple tools for chat and meetings
- Poor collaboration experience

TalkSpace solves these problems by combining **real-time chat, video conferencing, and screen sharing** into a single unified application using **WebSockets and WebRTC**.

---

## 🎯 Objectives

- Build a real-time communication platform
- Implement video conferencing and screen sharing
- Understand WebRTC peer-to-peer communication
- Use Socket.io for real-time signaling
- Design a scalable client–server architecture
- Deliver a responsive and user-friendly interface

---

## 🚀 Key Features

### 💬 Real-Time Chat
- Instant one-to-one messaging
- Typing indicators
- Online / offline user status
- No page refresh required

### 🎥 Video & Audio Calling
- One-to-one video conferencing
- Real-time audio & video streaming
- Camera and microphone controls
- Low-latency peer-to-peer connection

### 🖥 Screen Sharing
- Live screen sharing during video calls
- Ideal for presentations & collaboration
- Smooth real-time screen transmission

### 🔐 Security & UI
- User authentication
- Secure signaling
- Clean and modular codebase
- Responsive and modern UI

---

## 🛠 Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

### Backend
- Node.js
- Express.js
- Socket.io

### Real-Time Communication
- WebRTC (Video, Audio & Screen Sharing)

### Database
- MongoDB

---

## 🏗 System Architecture


Client (React.js)  
↕ WebRTC (Video / Audio / Screen)  
↕ Socket.io (Chat & Signaling)  
Server (Node.js + Express)  
↕  
MongoDB  

---

## Project Structure

TalkSpace/  
├── client/  
│   ├── src/  
│   ├── components/  
│   └── pages/  
├── server/  
│   ├── controllers/  
│   ├── models/  
│   ├── routes/  
│   └── socket/  
├── .env  
└── README.md  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/Rakeshivam/TalkSpace.git
cd TalkSpace

2. Install backend dependencies  
npm install

3. Install frontend dependencies  
cd client
npm install

4. Run the application  
npm run dev


Backend runs on: http://localhost:5000  
Frontend runs on: http://localhost:3000  

---

## Environment Variables

Create a `.env` file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


---

## Working Methodology

1. User registers or logs in
2. Backend authenticates the user
3. Socket.io establishes real-time connection
4. WebRTC signaling handled via Socket.io
5. Peer-to-peer video/audio connection established
6. Screen sharing stream transmitted in real-time
7. Chat messages delivered instantly

---

## Future Enhancements

- Group video conferencing
- File sharing during calls
- Push notifications
- End-to-end encryption
- Dark mode
- Mobile application

---

## Contributing

Contributions are welcome and appreciated.

Steps to contribute:
1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---


## Author

Rakeshivam  
GitHub: https://github.com/Rakeshivam  

---

⭐ Star this repository if you found it useful
