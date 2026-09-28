# 🍲 Food Donation System

A full-stack web app for building communities: create groups, share posts, and chat in real time.

![React](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?logo=react&logoColor=white)
![Node](https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-339933?logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB%20Atlas-47A248?logo=mongodb&logoColor=white)
![Socket.io](https://img.shields.io/badge/Realtime-Socket.io-010101?logo=socket.io&logoColor=white)

---

## ✨ Features

- 👤 **User profiles**: sign up, log in, and manage your profile
- 👥 **Interest-based groups**: create, discover, and join communities
- 📰 **Activity feed**: share posts and react to others
- 💬 **Real-time direct messaging**: instant chat powered by Socket.io
- 🧠 **Smart Community Engagement Engine**: feed ranking, group recommendations, and member matching

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React, Vite, react-router-dom, axios, socket.io-client |
| Backend | Node.js, Express, Socket.io |
| Database | MongoDB Atlas (Mongoose) |
| Dev tools | Nodemon, VS Code |

## 📁 Project Structure

```
Food donation system/
├── backend/     # Express API, MongoDB models, routes, Socket.io
└── frontend/    # React + Vite client
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- A [MongoDB Atlas](https://www.mongodb.com/atlas) cluster and database user

### 1. Clone the repository

```bash
git clone https://github.com/Pushkar8002/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Set up the backend

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/`:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secret_key
```

Start the server:

```bash
npm run dev
```

The API runs at `http://localhost:5000`.

### 3. Set up the frontend

Open a second terminal:

```bash
cd frontend
npm install
npm run dev
```

The app runs at `http://localhost:5173`.

## 🔌 API Overview

| Area | Purpose |
|------|---------|
| `/auth` | Register and log in |
| `/users` | Profiles |
| `/groups` | Create, list, and join groups |
| `/posts` | Feed posts and reactions |
| `/messages` | Direct messages (plus Socket.io events) |

## 📄 Documentation

Food Donation System was planned using the **Waterfall model**. Project documents include:

- Software Requirements Specification (IEEE 830 format)
- A 13-slide presentation covering the Waterfall phases, timeline, and risk assessment

## 🗺️ Roadmap

- [ ] Notifications
- [ ] Image uploads for posts and profiles
- [ ] Deployment (frontend + backend)
- [ ] Improved recommendation logic

## 👨‍💻 Author

**Pushkar Singh**
B.Tech CSE, Galgotias University

[LinkedIn](https://www.linkedin.com/in/pushkar-singh-80852732b/) · [GitHub](https://github.com/Pushkar8002) · pushkarsingh8002@gmail.com

---

⭐ If you found this project useful, consider giving it a star!
