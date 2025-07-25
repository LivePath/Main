 📍 LocationTracker – Real-Time Path & Safety Monitoring Web App

**LocationTracker**  is a MERN Stack web application that enables one person (Sharer) to share their destination and intended path, while another person (Tracker) monitors their journey in real time. The system triggers alerts if the sharer deviates from the route or reaches key points. It's designed for safety, reliability, and peace of mind in travel monitoring.

---

## 🚀 Key Features

- 🌐 Real-time Location Sharing using Google Maps
- 📌 Select Destination & Route
- 🔔 Route Deviation Alerts (via Firebase Notifications)
- ✅ Arrival Notifications at Key Points
- 📊 Trip History & Time Logging
- 🧭 Progressive Web App (PWA) Support for Background Location
- 🔒 Google Firebase Authentication

---

## 🛠️ Tech Stack

| Layer        | Tech Used                      |
|--------------|-------------------------------|
| Frontend     | React, Tailwind CSS            |
| Backend      | Node.js, Express.js, MongoDB   |
| Real-Time    | Socket.IO, WebSockets          |
| Auth/Alerts  | Firebase (Auth + Cloud Msg)    |
| Maps API     | Google Maps JavaScript API     |
| Deployment   | Vercel (Frontend), Render (Backend), MongoDB Atlas |

---

📁 Folder Structure

locationtracker/
├── frontend/ # React + Tailwind (User Interface)
├── backend/ # Express + MongoDB + Sockets (API + Logic)
├── docs/ # Presentations, reports, diagrams
├── deployment/ # Firebase configs, Render setup
└── README.md


---

## 🧪 How to Run Locally

## 🚩 Prerequisites:
- Node.js, npm
- MongoDB Atlas URI
- Google Maps API Key
- Firebase project (Auth + Messaging)

---

## 🔧 Frontend Setup
cd frontend
npm install
npm start

## 🔧 Backend Setup

cd backend
npm install
npm run dev

