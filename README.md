# ✔️ To-Do App

A fully functional, single-page Todo application built with React and TypeScript. It supports full CRUD operations, filtering, and robust state management for handling concurrent API requests and providing a great user experience.

The application uses an external REST API to persist data, simulating a real-world environment where data is managed remotely.

🔗 **Live Demo:** https://Julia-Hertseva.github.io/To-Do-App/
📂 **Repository:** https://github.com/Julia-Hertseva/To-Do-App

---

## 🧩 Features

This application provides a robust task-management experience with smooth UI interactions and reliable API synchronization.

🔹 Full CRUD Support

Create — Add new todos with an optimistic UI preview while awaiting API confirmation

Read — Load and render todos from the backend on startup

Update — Double-click to edit titles or toggle completion status

Delete — Remove individual todos seamlessly

🔹 Smart Filtering: Switch between All, Active, and Completed tasks

🔹 Bulk Actions for Productivity

Toggle All — Mark all tasks as completed or active in one click

Clear Completed — Remove all finished items instantly

🔹 Polished User Experience

Loading State — Shows a subtle loader while fetching data or processing requests

Optimistic Updates — Items visually react to API operations (e.g., dim while updating)

Error Handling — Contextual error messages appear and can be manually dismissed

Keyboard-friendly Editing —

Enter → save changes

Escape → cancel

Blur → auto-apply edits

---

## 🧩 Tech Stack

| Technology | Usage |
|-----------|-------|
| React | Component-based UI development and state management (using functional components and hooks) |
| TypeScript | Static typing for improved code quality and predictability |
| Vite | Fast build & dev environment |
| Bulma CSS | Base UI styles |
| SCSS | Preprocessor for writing modular and maintainable custom styles |
| Mate Academy API | Backend for todos |

---

## 📌 Main Components (Code Highlights)

- **App.tsx** — core logic, fetching todos, error/UI state
- **TodoList.tsx** — renders and updates list items
- **Todo.tsx** — editing, status toggle, loaders, delete action
- **NewTodo.tsx** — controlled input with focus restoring
- **Footer.tsx** — filters & Clear completed button :contentReference
- **UserWarning.tsx** — handles missing USER_ID cases

---

## 🔌 API Integration

To send requests correctly, register your **USER_ID** here:
https://mate-academy.github.io/react_student-registration

Then set your ID inside:

All requests include your unique user identifier.

---

## 🚀 Running the Project Locally

```bash
# Clone the repo
git clone https://github.com/Julia-Hertseva/To-Do-App

# Navigate into the folder
cd To-Do-App

# Install dependencies
npm install

# Start development server
npm start
