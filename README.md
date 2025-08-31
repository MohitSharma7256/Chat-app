# 📱 Real-Time Chat App

A **real-time 1:1 chat application** built with **React Native** (frontend) and **Node.js + Express + Socket.IO** (backend).
Messages are persisted in **MongoDB/Postgres**.

---

## 🚀 Features (MVP)

* **Authentication**: Register & Login (JWT-based)
* **User List**: View all registered users & start chat
* **Real-Time Messaging**: Powered by **Socket.IO**
* **Message Persistence**: Stored in database
* **Typing Indicator**: See when the other user is typing
* **Online/Offline Status**
* **Message Delivery & Read Receipts**
* **Basic UI**:

  * Auth Screens
  * Home (User list + last message)
  * Chat Screen (messages, input, typing, ticks)

---

## 🛠️ Tech Stack

### Frontend (React Native)

* React Native (Expo)
* React Navigation
* Axios (API calls)
* Socket.IO Client

### Backend (Node.js + Express)

* Express.js
* MongoDB / Postgres (for message & user storage)
* JWT Authentication
* Socket.IO (real-time communication)


## 📂 Project Structure

```
/chat-app
 ├── /mobile      # React Native frontend
 ├── /server      # Node.js backend
 ├── README.md    # Documentation
```


## 🔑 API Endpoints

### REST

* `POST /auth/register` → Register new user
* `POST /auth/login` → Login & get JWT token
* `GET /users` → Get all users
* `GET /conversations/:id/messages` → Get chat messages

### Socket Events

* `message:send` → Send new message
* `message:new` → Receive new message
* `typing:start` | `typing:stop` → Typing indicator
* `message:read` → Mark message as read

---

## ▶️ How to Run

### Backend

```bash
cd server
npm install
npm start
```

### Frontend

```bash
cd mobile
npm install
npm start
```


## 📹 Deliverables

  GitHub Repo**: Contains `/mobile` and `/server` folders.
  README.md**: Setup & usage instructions.
  Demo Video (≤5 min)**: Show login, user list, chat, typing, message delivery/read.


✨ Developed as part of assignment: Real-Time Chat App with React Native & Node.js
---

Would you like me to also **add some sample test users (JSON format)** in README (like `email`, `password`) for login demo? That way evaluator can tes
