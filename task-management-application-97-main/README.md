# Welcome to my project- TASK MANAGEMENT APPLICATION

## Overview
A web-based task management application where users can create, view, update, and delete tasks.

## 🎯 Objective
To build a full-stack application using **Next.js (Frontend), NestJS (Backend), and MongoDB (Database)** with **Redux Toolkit for state management** and **Jest for testing**.

## Project info

Setting up VS Code and Running The Application

```sh
# Step 1: VS Cose Setup
1. Install Visual Studio Code if you haven't already from code.visualstudio.com

2: Install recommended extensions:
-> JavaScript and TypeScript support: "JavaScript and TypeScript Nighter" by Microsoft
-> React support: "ES7+ React/Redux/React-Native snippets"
-> MongoDB: "MongoDB for VS Code"
-> REST Client: "REST Client" (for testing your API endpoints)
-> ESLint: "ESLint" (for code linting)
-> Prettier: "Prettier - Code formatter" (for consistent formatting)

# Step 2: MongoDB Setup on Mac
1. Download MongoDB Compass and connect it to VS Code.

# Step 4: Running the Application
npm install
npm run dev
```

## 🚀 Key Features

### **Frontend (Next.js + Redux Toolkit)**
✅ **Responsive UI** with the following pages:
- 🏠 **Home Page**: Displays a list of tasks (title & status).
- 📄 **Task Detail Page**: Shows task details (title, description, status).
- 🆕 **New Task Page**: Form to create a new task.
- ✏️ **Edit Task Page**: Form to update an existing task.

---

### **Backend (NestJS + MongoDB)**
✅ **REST API Endpoints**:
- `POST /tasks` → Create a new task.
- `GET /tasks` → Fetch all tasks.
- `GET /tasks/:id` → Fetch a single task.
- `PUT /tasks/:id` → Update a task.
- `DELETE /tasks/:id` → Delete a task.

✅ **MongoDB Integration**:
- Uses **Mongoose** to interact with MongoDB.
- Defines a `Task` schema with:
  - `id`: Unique identifier.
  - `title`: Task title (required).
  - `description`: Task details (required).
  - `status`: Task status (`pending`, `in-progress`, `completed`).

✅ **Validation & Error Handling**:
- Uses **DTOs & class-validator** for input validation.
- Returns **404 error** for missing tasks.
---

## 🧪 Testing
✅ **Unit & Integration Tests using Jest**:
- Backend: Tests service functions (create, update, delete tasks).
- Frontend:
  - Component testing (task form, task list).
  - Redux slice & async thunk tests.

---

## 🛠️ Tech Stack
- **Frontend**: Next.js, Redux Toolkit, Axios
- **Backend**: NestJS, MongoDB, Mongoose
- **Testing**: Jest
- **Language**: TypeScript
- **DevOps**: Docker (optional for containers)

---
## 🎁 Bonus Features Asked
✨ **Pagination** for task list.  
🔍 **Search & filter** tasks by title/status.  
🐳 **Docker support** for frontend, backend, and MongoDB. 

## 🎁 Additional Features Added to the Bonus Features
✨ **Dark/light theme** with a toggle button in the header.  
📌 **Multiple view options**: List, Grid, Kanban, and Calendar.  
🎤 **Voice input** support for adding tasks using the browser's Speech Recognition API.  
📊 **Drag-and-drop Kanban boards** for visual task management.  
📱 **Responsive design** that adapts to all screen sizes.  
🎭 **Microinteractions and animations** for better UX using Framer Motion.  
♿ **Accessibility improvements** with ARIA labels and keyboard navigation.  

# Backend Setup (NestJS)
## Open terminal.
cd backend
npm install

Run Backend:
npm run start:dev

# Frontend Setup (Next.js)
cd frontend
npm install
## RUN FRONTEND:
npm run dev

