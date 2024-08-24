# ToDO-App
## Description

This project is a simple yet efficient Todo application built using React. It allows users to manage their daily tasks by adding, updating, deleting, and marking them as completed. The app stores all tasks in the browser's localStorage, ensuring that the list is preserved even after the page is refreshed.

### Key Features:
- **Add Todos:** Easily add new tasks to your todo list.
- **Update Todos:** Modify existing tasks to keep your list accurate.
- **Delete Todos:** Remove tasks that are no longer needed.
- **Toggle Completion:** Mark tasks as completed or uncompleted with a single click.
- **Local Storage Persistence:** Your tasks are saved in the browser's localStorage, so your list remains intact even after a page refresh.
- **Responsive Design:** The application is responsive and works well on various screen sizes.

### Components:
- **App Component:** The main component that holds the entire application logic and renders the UI.
- **TodoForm Component:** A form component to input new tasks.
- **TodoItem Component:** A component that displays individual tasks with options to update, delete, or mark as completed.
- **TodoProvider Context:** A context provider that shares the todos and related functions across components.

### Technologies Used:
- **React:** For building the user interface.
- **CSS:** For styling the application.
- **JavaScript:** For handling the application's logic.
- **LocalStorage:** For persisting the todo list across browser sessions.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
- Node.js installed on your local machine.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/todo-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd todo-app
   ```
3. **Install the dependencies:**
   ```bash
   npm install
   ```

### Running the App
1. **Start the development server:**
   ```bash
   npm start
   ```
2. **Open your browser and navigate to:**
   ```bash
   http://localhost:3000
   ```

### Usage
- **Add a Todo:** Use the input form to type a new task and click the "Add" button.
- **Mark as Completed:** Click on a todo item to toggle its completion status.
- **Edit a Todo:** Click on the edit icon next to a task to update its content.
- **Delete a Todo:** Click on the delete icon next to a task to remove it from the list.


---

