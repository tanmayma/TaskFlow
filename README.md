# 🚀 TaskFlow – Task Management Application

TaskFlow is a modern and user-friendly **Task Management Application** built with **React.js**. It helps users create, organize, prioritize, complete, and manage their daily tasks efficiently.

The application uses **LocalStorage** to persist task data, allowing tasks to remain available even after refreshing the browser.

---

## ✨ Features

### 📝 Task Input
- Add new tasks using a simple input field.
- Prevent empty or duplicate tasks.
- Quickly add tasks using the submit button.

### 📋 Task List
- Display all tasks dynamically.
- View task names and their completion status.
- Mark tasks as completed.
- Delete tasks when they are no longer required.

### 💾 Persistent Data
- Uses **Browser LocalStorage** to store tasks.
- Tasks remain available even after refreshing or reopening the page.

### 📊 Progress Tracker
- Displays the percentage of completed tasks.
- Progress updates automatically whenever a task is completed or added.

### 🕒 Task History
- View previously completed tasks.
- Restore completed tasks when needed.
- Delete tasks permanently from the history.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ⚛️ React.js | Frontend development |
| 🟨 JavaScript | Application logic |
| 🌐 HTML5 | Page structure |
| 🎨 CSS3 | Styling and responsive UI |
| 💾 LocalStorage | Persistent task storage |
| 🔧 Git | Version control |
| 🐙 GitHub | Source code management & deployment |
| 🟢 Node.js & npm | Development environment and package management |

---

## 📂 Project Structure

```text
TaskFlow/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── TaskForm.jsx
│   │   ├── TaskList.jsx
│   │   ├── TaskItem.jsx
│   │   ├── ProgressTracker.jsx
│   │   └── TaskHistory.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── App.css
│   └── index.css
│
├── package.json
├── package-lock.json
└── README.md
