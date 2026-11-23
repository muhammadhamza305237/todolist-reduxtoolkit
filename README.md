# 📝 Todo List (Redux Toolkit)

A task list web application built with **React**, **Redux Toolkit**, **React Redux**, **Tailwind CSS**, and **Vite**, demonstrating centralized state management with `configureStore`, `createSlice`, and `nanoid`.

**Live Demo:** https://todo-list-redux-tool-kit.vercel.app

## 🛠️ Tech Stack
- **Frontend:** React 18 (Vite), Tailwind CSS
- **State Management:** Redux Toolkit (`@reduxjs/toolkit`), React Redux (`react-redux`)
- **UI & Icons:** Tailwind CSS utility styling, inline SVG action icon

## ✨ Key Features
- **Add Todos:** Controlled input form (`AddTodo`) dispatches `addTodo` with a unique ID generated via `nanoid` and clears the input on submit.
- **View & Delete Todos:** Renders tasks from the Redux store via `useSelector` and removes items by ID using `removeTodo` on button click.
- **Centralized Redux Store:** Configured with `configureStore`, wrapped at the root with `<Provider>`, and updated through `todoSlice` reducers.

## 🚀 How to run locally
1. Clone the repository
2. Run `npm install`
3. Run `npm run dev`