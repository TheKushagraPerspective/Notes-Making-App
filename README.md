# Notes Making App 📝

A full-stack notes-making application built with **React (frontend)** and **Node.js + Express + MongoDB (backend)**.  
This app allows users to create, manage, and store notes securely with JWT authentication.

---

##  Features
- User authentication (JWT-based)
- Create, read, update, and delete notes
- MongoDB database integration
- Environment variable support for configuration
- Simple and responsive frontend with React

---

##  Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/TheKushagraPerspective/Notes-Making-App.git
cd Notes-Making-App

```

Frontend Setup (React)

Navigate to the frontend folder:
```bash
cd frontend
```

Install dependencies:
```bash
npm install
```

Create a .env file inside the frontend folder with the following:

```bash
VITE_BASE_URL=http://localhost:5000
```

(Change the base URL according to your backend running URL)

Run the frontend:
```bash
npm start
```

Backend Setup (Node.js + Express)

Navigate to the backend folder:
```bash
cd backend
```

Install dependencies:
```bash
npm install
```

Create a .env file inside the backend folder with the following:
```bash
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
VITE_BASE_URL=http://localhost:3000
```

(Adjust values as per your setup)

Run the backend server:
```bash
node server.js
```

Tech Stack

Frontend: React

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT

 Usage

Start backend first (node server.js).

Start frontend (npm start).

Open http://localhost:3000
 in your browser.

Register/login and start creating notes!

 Scripts

Frontend:

npm start   # start development server
npm run build   # build for production


Backend:

node server.js   # start backend server

 License

This project is licensed under the MIT License.


Would you like me to also add **screenshots & API documentation section** in the README (for routes lik

