# React Task Tracker

A small React application created for INEW-2434 Module 2. The application allows users to create and manage tasks while demonstrating React components, props, state, event handling, forms, and lists.

## Features

- View existing tasks
- Add new tasks
- Prevent empty or whitespace-only tasks
- Mark tasks as completed
- Mark completed tasks as active again
- Delete tasks
- View active, completed, and total task counts
- Filter tasks by All, Active, or Completed
- Display a helpful message when no tasks remain
- Responsive layout for desktop and smaller screens

## React Concepts Practiced

This project uses:

- React components
- Props
- `useState`
- Event handlers
- Controlled form inputs
- Conditional rendering
- `map()` and `filter()`
- Stable task IDs

## Project Structure

```text
src/
├── components/
│   ├── TaskForm.jsx
│   ├── TaskList.jsx
│   └── TaskCard.jsx
├── App.jsx
├── index.css
└── main.jsx