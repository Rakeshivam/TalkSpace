# TalkSpace 🚀
### Real-Time Chat, Video Conferencing & Screen Sharing Platform

TalkSpace is a full-stack real-time communication platform that provides instant messaging, video conferencing, audio calling, and live screen sharing. The application is built using modern web technologies to deliver low-latency, secure, and seamless real-time communication.

This project demonstrates real-world implementation of WebRTC, Socket.io, and scalable full-stack architecture, making it suitable for learning, final-year projects, and production-ready systems.

---

## Overview

Modern applications require more than simple text-based messaging. Users expect real-time chat, video meetings, and screen sharing within a single platform.

TalkSpace integrates:
- Real-time chat
- Video & audio calling
- Live screen sharing
- Secure authentication
- Responsive UI

All communication happens without page refresh, ensuring a smooth and interactive experience.

---

## Problem Statement

Traditional communication systems suffer from high latency, lack of real-time updates, and dependency on multiple tools for chat and video meetings.

TalkSpace solves these problems by combining real-time messaging, video conferencing, and screen sharing into a single, unified platform using WebSockets and peer-to-peer communication.

---

## Objectives

- Build a real-time communication platform
- Implement video conferencing and screen sharing
- Understand WebRTC peer-to-peer communication
- Use Socket.io for real-time signaling
- Design a scalable client-server architecture
- Provide a responsive and user-friendly interface

---

## Key Features

### Real-Time Chat
- Instant one-to-one messaging
- Typing indicators
- Online/offline user status
- No page refresh required

### Video & Audio Calling
- One-to-one video conferencing
- Real-time audio and video streaming
- Camera and microphone controls
- Low-latency peer-to-peer connection

### Screen Sharing
- Live screen sharing during video calls
- Useful for presentations and collaboration
- Smooth real-time screen transmission

### Security & UI
- User authentication
- Secure signaling
- Responsive and modern UI
- Clean and modular codebase

---

## Tech Stack

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

## System Architecture

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

## Installation & Setup

1. Clone the repository  
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

## Code of Conduct

### Our Pledge
We pledge to make participation in this project a harassment-free experience for everyone, regardless of age, gender, disability, ethnicity, religion, or level of experience.

### Our Standards
Examples of behavior that contribute to a positive environment include:
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Accepting constructive criticism gracefully
- Focusing on what is best for the community

### Unacceptable Behavior
- Harassment, discrimination, or hate speech
- Trolling or insulting comments
- Publishing others’ private information without permission
- Any unprofessional conduct

### Enforcement
Project maintainers may take appropriate action against any behavior that violates this Code of Conduct.

---

## License (MIT)

MIT License

Copyright (c) 2026 Rakesh Kushwaha

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so.

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

---

## Author

Rakeshivam  
GitHub: https://github.com/Rakeshivam  

---

⭐ Star this repository if you found it useful
