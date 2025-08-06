# 📌 Task Management System

Welcome to **Task Management**, a powerful and scalable **task management system** built with the **MERN Stack** (MongoDB, Express.js, React, Node.js). Designed for real-world B2B SaaS platforms, Task management enables seamless **workspace collaboration**, **project tracking**, and **role-based task management** — with modern tools and architecture.

---

## 🌟 Key Features

- 🔐 **Authentication**: Google Sign-In, Email & Password
- 🏢 **Workspace Management**: Create & manage multiple teams/workspaces
- 📊 **Projects & Epics**: Organize projects with flexible structures
- ✅ **Task Management**: CRUD, status, priority, assignee
- 👥 **Roles & Permissions**: Owner, Admin, Member
- ✉️ **Member Invitations**: Invite collaborators to workspaces
- 🔍 **Search & Filters**: Filter by status, priority, assignee
- 📈 **Analytics Dashboard**: Insightful project stats
- 📅 **Pagination & Load More**: Efficient task navigation
- 🔒 **Secure Session Handling**: Cookie-based sessions
- 🚪 **Logout & Termination**: Clear sessions on logout
- 🌱 **Test Data Seeding**: Quickly populate sample data
- 💾 **Mongoose Transactions**: Ensure robust data integrity
- 🌐 **MERN Stack + TypeScript**: Modern full-stack architecture

---

## 🚀 Tools & Technologies

| Stack       | Description                                |
|-------------|--------------------------------------------|
| 🟢 Node.js   | Scalable backend runtime                   |
| ⚛️ React.js  | Dynamic frontend library                   |
| 🍃 MongoDB   | NoSQL database for flexible storage        |
| 📦 Mongoose  | Elegant MongoDB object modeling            |
| 🔐 Google OAuth | Google Sign-In integration             |
| 🧑‍💻 TypeScript | Type-safe development on both ends     |
| 🎨 TailwindCSS & Shadcn UI | Beautiful, responsive design |
| ⚡ Vite.js   | Fast frontend tooling                      |

---

## 🔄 Getting Started

### Setup Environment Variables

Create a `.env` file in the root of your **backend** folder with the following content:

```env
PORT=8000
NODE_ENV=development

MONGO_URI="mongodb+srv://<username>:<password>@<cluster>.mongodb.net/teamsync_db"

SESSION_SECRET="session_secret_key"

GOOGLE_CLIENT_ID=<your-google-client-id>
GOOGLE_CLIENT_SECRET=<your-google-client-secret>
GOOGLE_CALLBACK_URL=http://localhost:8000/api/auth/google/callback

FRONTEND_ORIGIN=http://localhost:3000
FRONTEND_GOOGLE_CALLBACK_URL=http://localhost:3000/google/callback
```
Run the Application
Install all required packages and start your development server.

```env
npm install
```

```env
npm run dev
```
## 🌐 Deployment

This project is live and can be accessed at:  
👉 [https://team-sync-iota.vercel.app/](https://team-sync-iota.vercel.app/)
