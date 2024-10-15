# Todo App Without Firebase 🗒️

Welcome to the **Todo App** repository! 🎉 This project features a simple and efficient task management application that allows users to create, manage, and delete their to-do items without relying on Firebase.

## Project Overview 📚

This repository includes:
- **HTML** and **CSS** for the user interface 🌐
- **JavaScript** for managing to-do tasks and user interactions 🔍
- Features to add, complete, and delete tasks in a user-friendly manner ✅

## Understanding the Todo App 🤔

The **Todo App** is designed to help users organize their tasks efficiently. Users can add tasks, mark them as complete, and remove them when they are no longer needed.

### How the Todo App Works 🔄

The application follows these steps:
1. Users can input tasks into a text field.
2. Tasks are added to the list and displayed dynamically.
3. Users can complete or delete tasks with a click.

### Example Features 🗂️

Here are some key features of the Todo App:
- **Add Tasks**: Input a new task and click "Add."
- **Complete Tasks**: Mark a task as complete by clicking the checkbox.
- **Delete Tasks**: Remove tasks from the list with a delete button.

## JavaScript Implementation 💻

Here’s a core JavaScript function for managing tasks:

```javascript
function addTask(task) {
    // Add a new task to the list
    const taskItem = document.createElement('li');
    taskItem.textContent = task;
    document.getElementById('taskList').appendChild(taskItem);
}

// Example usage:
addTask("Buy groceries"); // Adds "Buy groceries" to the task list.
```

## Usage Instructions 🛠️

To run the Todo App:
1. Open the `index.html` file in your web browser.
2. Enter a task in the input field and click "Add" to include it in your list.
3. Mark tasks as complete or delete them as needed.

## Contact Information 📞

For questions or suggestions about this project:

- **Email**: muhammadeshareeb986@gmail.com 📧
- **LinkedIn**: [Muhammad Eshareeb](https://www.linkedin.com/in/muhammadeshareeb986/) 🦸‍♂️

Happy Task Management! 🎉
