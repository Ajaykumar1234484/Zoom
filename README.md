Zoom Clone – Real-Time Video Conferencing Application

This is a full-stack video conferencing web application built using a modern MERN-style architecture.
The application allows users to authenticate, create meeting rooms, and communicate in real-time using video, audio, and live events.

The project focuses on real-time communication, clean backend structure (MVC), and reusable frontend components.

🚀 Key Features

User authentication and protected routes

Create and join secure meeting rooms

Real-time video and audio communication

Live signaling using Socket.io

Responsive and component-based UI

Structured backend using MVC pattern

🛠️ Tech Stack
Frontend

React – Building interactive UI components

React Router – Client-side routing

CSS Modules – Scoped component styling

Context API – Authentication state management

JavaScript (ES6+)

Backend

Node.js – Runtime environment

Express.js – REST API framework

MongoDB – NoSQL database

Mongoose – MongoDB object modeling

Socket.io – Real-time event handling

Real-Time Communication

WebRTC – Peer-to-peer video/audio streaming

Socket.io – Signaling and live communication events

🏗️ Architecture

Backend follows MVC (Model-View-Controller) structure

Frontend is built using component-based architecture

Authentication handled using Context API

Protected routes implemented using Higher-Order Components (HOC)

📂 Project Structure
Zoom
 ├── backend
 │    ├── models
 │    ├── controllers
 │    ├── routes
 │    └── src
 │
 ├── frontend
 │    ├── components
 │    ├── context
 │    └── pages
 │
 └── README.md

⚙️ Getting Started
1️⃣ Clone the repository
git clone https://github.com/Ajaykumar1234484/Zoom.git
cd Zoom

2️⃣ Start Backend
cd backend
npm install
npm run dev


Server runs on:

http://localhost:8000

3️⃣ Start Frontend

Open a new terminal:

cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔐 Environment Variables

Create a .env file inside the backend folder:

PORT=8000
MONGO_URI=your_mongodb_connection_string

🎯 Project Purpose

This project was built to strengthen understanding of:

Real-time communication using WebRTC

Event-based architecture with Socket.io

Full-stack application integration

Authentication and protected routing

Clean backend structure using MVC

 
