# 📱 Social Media App

A fully-typed social media backend built with TypeScript and Node.js, featuring real-time messaging, group chats, and role-based access control.

---

## 🚀 Features

- 📝 Posts, likes, comments, and follow/unfollow functionality
- 💬 Real-time private messaging and group chat via Socket.io
- 🔐 Google OAuth and JWT authentication
- 👥 Role-Based Access Control (RBAC)
- ⚡ Optimized MongoDB queries for high-frequency endpoints
- ✅ Request validation using Zod
- 📊 GraphQL API integration

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Language | TypeScript |
| Runtime | Node.js |
| Framework | Express.js |
| Database | MongoDB, Mongoose |
| Real-time | Socket.io |
| API | REST, GraphQL |
| Auth | JWT, Google OAuth, RBAC |
| Validation | Zod |

---

## 📁 Project Structure

```
src/
├── modules/
│   ├── user/
|   ├── auth/
│   ├── post/
│   ├── comment/
│   ├── chat/
|   ├── gateway/
│   └── graphql/
|── DB/
├── utils/
├── middleware/
└── index.ts
```

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/Eman-mohamed33/SocialMediaApp.git

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run the app
npm run dev
```

---

## 👩‍💻 Author

**Eman Gesraha** · [LinkedIn](https://linkedin.com/in/eman-gesraha) · [GitHub](https://github.com/Eman-mohamed33)
