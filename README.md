# 🌟 Glimsee – Share Your Life Goals

**Glimsee** is a full-stack web application that allows users to share their short-term and long-term life goals. Users can interact with each other by posting goals, uploading pictures, liking/saving posts, commenting, and rating places they've visited. Think of it as a blend of Instagram and a personal goals journal.

---

## 🚀 Features

- 🔐 User registration and login
- 🏠 Instagram-style scrollable home feed
- 📷 Upload and share life goal posts with images
- ❤️ Like, comment, and save posts
- 📍 Explore and rate places users have traveled to
- 🧑‍💻 Personal profile and vertical dashboard navigation
- ✉️ Messages, notifications, and more (modular for expansion)

---

## 🛠️ Installation & Run Instructions

### ✅ Requirements

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)
- Any terminal or code editor (e.g. VS Code)

### 📦 Steps to Install

1. **Clone the project**

   ```bash
   git clone https://github.com/your-username/glimsee.git
   cd glimsee
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Create a `.env` file in the root directory**

   ```env
   MONGO_URI=mongodb://localhost:27017/glimsee
   ```

   Or use your MongoDB Atlas URI.

4. **Start the server**

   ```bash
   npm start
   ```

5. **Visit in your browser**
   ```
   http://localhost:3000
   ```

---

## 👥 Team Members & Contributions (Equal Contribution)

Each team member contributed equally to the design, development, and testing of the application.

- **Elaine Nankanja**  
  UI/UX design, frontend layout, testing, and feature integration

- **Afnan Siddiqui**  
  Backend routes, database models, and server logic

- **AbdulRahim Mohsin**  
  Authentication, session management, frontend features, and deployment prep

- **Rania Rejdal**  
  Dashboard and explore features, comment/like handling, and documentation

All members collaboratively worked on the app structure, code reviews, bug fixing, and final polishing.

---

## 📂 Project Structure Overview

```
glimsee/
│
├── models/             # MongoDB Mongoose models
├── routes/             # Express routes (auth, users, posts, etc.)
├── views/              # EJS templates
├── public/             # Static assets (CSS, JS, images)
├── controllers/        # Business logic (optional separation)
├── .env                # Environment variables
├── app.js              # Main server setup
├── package.json        # Project dependencies and scripts
└── README.md           # This file
```

---

## 💡 License

This project is for educational purposes only and not intended for production use.

---
