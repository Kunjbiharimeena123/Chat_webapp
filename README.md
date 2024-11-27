# Real-Time Chat Application (MERN Stack)

## Project Overview

This is a **real-time chat application** built using the **MERN** stack (MongoDB, Express, React, Node.js) with **Socket.io** for real-time communication. It allows users to register, log in, and send messages to other users in real-time, while maintaining chat history in the database. The app also shows users as **online** or **offline** based on their connection status.

---

## Features

- **User Authentication**:
  - Register and log in using **JWT (JSON Web Tokens)**.
  - User credentials are securely stored in MongoDB with password hashing using **bcrypt**.
  
- **Real-Time Messaging**:
  - Send and receive messages instantly using **Socket.io** for real-time communication.
  - View chat history stored in MongoDB when users log back in.
  
- **Online Presence Indicator**:
  - Users are shown as **online** or **offline** based on their connection status.
  - Broadcasting of user status updates to all connected clients.

- **Minimalist Chat UI**:
  - Simple and functional chat interface built with **React**.
  - Display chat messages with **timestamps** and **auto-scrolling** to the latest message.

---

## Technologies Used

- **Frontend**:
  - React
  - Socket.io-client
  - HTML5, CSS3

- **Backend**:
  - Node.js
  - Express
  - Socket.io
  - MongoDB (for database storage)

- **Authentication**:
  - JWT (JSON Web Tokens)
  - bcrypt (for password hashing)

- **Deployment**:
  - Frontend: **Netlify**
  - Backend: **Heroku** (or any other hosting provider)

---

## Installation and Setup

### Prerequisites

- Node.js (version >= 14.x)
- MongoDB (for local development) or a MongoDB Atlas account for cloud database hosting
- Git (for version control)

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/chat-app.git
cd chat-app

## run process:
cd server
npm install
PORT=5000
MONGO_URI=mongodb://localhost:27017/chat-app  # Or MongoDB Atlas URI
JWT_SECRET=your_jwt_secret_key
npm start
cd client
npm install
npm start




---

### **Explanation of Sections:**

1. **Project Overview**: Provides a summary of the project, highlighting the main features like real-time messaging, authentication, and user presence.
2. **Features**: Describes key features of the app, including authentication, real-time messaging, and online presence.
3. **Technologies Used**: Lists the technologies and libraries used in the project, including React, Node.js, Express, MongoDB, Socket.io, JWT, and bcrypt.
4. **Installation and Setup**: Step-by-step instructions on how to set up the project on a local machine, including backend and frontend setup, environment variables, and how to run the application locally.
5. **Usage**: Explains how to use the app after setting it up, including how to register, log in, send messages, and use the chat interface.
6. **Optional Features**: Lists additional features like typing indicators, image upload support, and read receipts.
7. **Deployment**: Instructions for deploying both the frontend and backend to platforms like **Netlify** and **Heroku**.
8. **Testing and Troubleshooting**: Offers guidance on testing the app and troubleshooting common issues.
9. **Contributing**: Invites others to contribute to the project and encourages best practices for collaboration.
10. **License and Acknowledgments**: Includes licensing details and thanks to the creators of the technologies used in the project.

---
