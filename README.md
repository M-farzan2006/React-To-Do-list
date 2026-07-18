# Tasklist — React To-Do List

A clean, fully functional to-do list built with React (functional components + hooks).

## Features
- Add tasks (empty tasks blocked, inline error message)
- Mark tasks complete (visual strikethrough)
- Delete tasks instantly
- Edit tasks (double-click a task, or use the pencil icon)
- Filter: All / Pending / Completed
- Persists to `localStorage` — tasks survive a page refresh
- Responsive, accessible (keyboard focus states, `aria-*` attributes)

## Folder structure
```
todo-app/
├── index.html
├── package.json
├── vite.config.js
├── src/
│   ├── main.jsx
│   ├── App.jsx            # state management lives here
│   ├── index.css
│   └── components/
│       ├── TaskInput.jsx
│       ├── TaskList.jsx
│       ├── TaskItem.jsx
│       └── FilterBar.jsx
```

## Run locally
```bash
npm install
npm run dev
```
Open the printed local URL (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview   # optional: preview the production build locally
```
