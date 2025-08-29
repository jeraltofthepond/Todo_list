### 📝 **Project Overview**

This project is a to-do list application built with **React** and **TypeScript**, showcasing both fundamental and advanced concepts of modern React development. The app features state management, a clean component architecture, and data persistence using local storage. Styling is handled with the **Tailwind CSS** framework, and the project is built and served using **Vite**.

---

### 💻 **Tech Stack**

* **React:** The core library for building the user interface.
* **TypeScript:** A superset of JavaScript that adds static typing, improving code quality and catching errors early.
* **Tailwind CSS:** A utility-first CSS framework for rapid and consistent styling.
* **Vite:** A next-generation frontend tool that provides a fast development environment.
* **Node.js:** The runtime environment for running the application.
* **Lucide React:** An icon library for sleek, visual icons.
* **ESLint:** A linter to enforce code style and catch potential issues.

---

### ✨ **Key Concepts & Techniques**

* **Component-Based Architecture:** The app is broken down into reusable and modular components like `App.tsx`, `TodoList.tsx`, and `TodoItem.tsx` for maintainability.
* **Declarative UI:** The project embraces React's declarative approach, where the UI automatically updates based on the application's state.
* **Unidirectional Data Flow:** State flows in a single direction, from parent components to child components via **props**, ensuring predictable behavior.
* **State Management with Hooks:** The **`useState`** hook is used to manage and update the application's state.
* **Side Effects with `useEffect`:** The **`useEffect`** hook handles side effects, such as saving the to-do list to local storage to ensure data persistence.
* **Custom Hooks:** A custom hook (`useTodos`) is used to abstract and reuse state-related logic, leading to cleaner and more organized code.
* **Conditional Rendering:** UI elements are dynamically rendered based on the state, for example, displaying a "delete all completed" button only when completed tasks exist.

---

### 🚀 **Features**

* ➕ Add new to-do items to the list.
* ✅ Toggle a to-do item's completed status.
* 🗑️ Delete individual to-do items.
* 🧹 Clear all completed to-dos with one click.
* ⬇️ Completed items are automatically sorted to the bottom of the list.
* 📝 A helpful message is displayed when the list is empty.
* 🔄 The to-do list persists in local storage, so tasks are safe even after the page is refreshed.