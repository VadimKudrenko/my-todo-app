# 📝 Todo App

A simple yet functional Todo application built with React and TypeScript.
This project demonstrates working with an external API.
Users can create, view, complete, delete, and filter todos based on their status.

## 🔗 Live Preview

[Check the demo here](https://vadimkudrenko.github.io/my-todo-app)

## 🛠️ Technologies Used

### Core
- **React** (v18+) – UI library
- **TypeScript** (v5+) – Type safety
- **SCSS** – Component-based styling

### Data Handling
- **External REST API** – Used for fetching, updating, and deleting todos
- **Axios** – For performing HTTP requests

### UI/UX
- **Transition Group** – It is used to implement smooth animations during any interactions with todos.

### Development & Deployment
- **Vite** – Build tool
- **ESLint** – Code quality & linting
- **GitHub Pages** – Hosting and deployment

## ✨ Features

- View all previously created todos pulled from an API
- Add new todos using an input field
- Mark todos as completed using checkboxes
- **Sorting**: Filtertodos by their status: All / Active / Completed
- Delete completed todos with a single click
- Real-time UI updates based on server-side data
- Minimalistic and responsive design


## ✨ Features

- **Classic Todo**:  Users can add new tasks, edit existing ones, and remove any todo items at any time.

- **Filter todos by status**: Filter the list to show all tasks, only completed, or only active todos.

- **Server-side persistence**: All todos are stored on a remote server and persist even after a page reload.

- **Toggle completion status**: Each todo has a status that allows users to mark it as completed or return it to active.

- **Real-time UI updates**: The interface immediately reflects changes like status toggles, additions, or deletions based on API responses.

- **Minimalistic and pleasant design**: The layout responds to every user action with smooth animations that improves the user experience.


## 🚀 Getting Started

Follow these instructions to run the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/VadimKudrenko/my-todo-app.git
```
```bash
cd my-todo-app
```

### 2.Install dependencies:
```bash
npm install
# or
yarn install
```

### 3.Run the project locally:
```bash
npm start
# or
yarn start
```
