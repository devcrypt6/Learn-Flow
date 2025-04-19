Here’s the updated `README.md` for you to copy and paste directly into your project, with the correct link:

```markdown
# MERN Video Learning Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Issues](https://img.shields.io/github/issues/devcrypt6/Learn-Flow)](https://github.com/devcrypt6/Learn-Flow/issues) [![Build](https://img.shields.io/github/actions/workflow/status/devcrypt6/Learn-Flow/ci.yml)](https://github.com/devcrypt6/Learn-Flow/actions)

## 🚀 Project Overview

A modern, dynamic web platform built on the MERN stack, featuring:

- **Secure OAuth 2.0 Google Sign‑In** for seamless authentication
- **Role-Based Access Control (RBAC)** differentiating **Creators** and **Students**
- **Content Management**: Creators can upload and post learning videos; Students can browse and view content
- **Hierarchical Threaded Comments**: Infinite nesting for discussions, ensuring organized conversations

Designed with privacy and user experience in mind, this platform offers a polished, professional interface for both content creators and learners.

---

## 🛠️ Tech Stack & Dependencies

| Layer         | Technology                   |
|---------------|------------------------------|
| Frontend      | React, React Router, Tailwind CSS |
| Backend       | Node.js, Express.js          |
| Database      | MongoDB, Mongoose            |
| Auth & Security | OAuth 2.0 (Google), JWT     |
| Testing       | Jest, Supertest              |
| Deployment    | Docker, Docker Compose       |

### 📋 Requirements

- Node.js v16.x or higher
- npm v8.x or higher (or yarn)
- MongoDB v5.x or a MongoDB Atlas account
- A Google Cloud project with OAuth 2.0 credentials (Client ID & Secret)
- Optional: Docker & Docker Compose for containerized setup

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/devcrypt6/Learn-Flow.git
   cd Learn-Flow
   ```

2. **Install dependencies**
   ```bash
   # From root
   npm install
   # Navigate to client
   cd client && npm install
   # Back to root for server
   cd ../server && npm install
   ```

3. **Configure environment variables**
   Create a `.env` file in the `server` directory:
   ```ini
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   ```

4. **Run in development**
   ```bash
   # From root
   npm run dev
   ```
   This will start the backend on port 5000 and the React app on port 3000 (with proxying).

---

## 📂 Folder Structure

```text
Learn-Flow/
├── client/             # React frontend
│   ├── public/         # Static assets
│   └── src/            # Components, pages, hooks, styles
├── server/             # Express backend
│   ├── controllers/    # Route handlers
│   ├── models/         # Mongoose schemas
│   ├── routes/         # API endpoints
│   ├── middleware/     # Auth, error handling
│   └── utils/          # Helpers, config
├── .env.example        # Example env file
├── docker-compose.yml  # Docker setup
└── README.md
```

---

## 🎬 Usage

1. **Sign in with Google**: Click the “Sign in with Google” button on the landing page.
2. **Switch Roles**: Creators can upload videos; Students can browse and comment.
3. **Post & Engage**: Use infinite threaded comments to discuss lessons in depth.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "feat: add new feature"`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

Please adhere to the existing code style and write tests for new features.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## ✉️ Contact

Created and maintained by [Your Name](https://github.com/devcrypt6). For support, open an issue or contact me at your.email@example.com.
```

Now you can simply copy and paste this directly into your project’s `README.md` file. Feel free to make adjustments if necessary!
