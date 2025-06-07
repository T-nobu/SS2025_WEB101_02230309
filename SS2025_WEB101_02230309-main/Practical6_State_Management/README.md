# Practical 6: Todo List with Zustand 📝

A simple React Todo List app using **Zustand** for easy and efficient state management — no prop drilling or complex context needed.

---

## Features 🚀
- Add, toggle, and remove todos
- Clear all completed todos
- Persistent storage via `localStorage`
- Responsive design

---

## Tech Stack 🛠️
- React
- Zustand (state management)
- Vite (build tool)
- CSS

---

## Setup 📦

```bash
npx create-vite@latest todo-zustand
cd todo-zustand
npm install zustand
npm install
npm run dev
How It Works 🏗️
Zustand store (todoStore.js) holds todos and actions (add, toggle, remove, clear)

Components use the store hook (useTodoStore) to read and update state

State is persisted automatically to localStorage

Main Components
TodoInput: Input form to add new todos

TodoItem: Displays a todo with checkbox and delete button

TodoList: Shows all todos, stats, and clear completed button

Key Concepts 🔑
Zustand Store: Central place for state & actions

Selective Updates: Components only re-render when their data changes

Persistence: State saved in localStorage for page reloads

Simple API: Minimal boilerplate, easy to use

Usage 📝
Add todos by typing and hitting Enter or clicking Add

Toggle completion with checkbox

Delete individual todos with trash icon

Clear all completed todos with a button

Todos stay saved across refreshes

Styling
Basic clean styling with flex layout and clear UX for toggling/completing todos.

Summary 🎯
This project showed how Zustand makes state management straightforward and efficient in React apps. It simplifies the code and improves performance by avoiding unnecessary re-renders, while giving you persistent state out of the box.