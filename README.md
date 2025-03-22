# Simple-To-Do-List


A simple To-Do List application built using PHP and JSON for file storage. Users can add, mark as done/undone, and delete tasks. The tasks are saved in `tasks.json` to persist data even after reloading the page.

## Features
- **Add Task**: Users can enter a task and add it to the list.
- **Mark Task as Done/Undone**: Clicking on a task toggles its completion status.
- **Delete Task**: Users can remove tasks from the list.
- **Persistent Storage**: Tasks are saved in a `tasks.json` file.
- **Simple UI**: Styled using [Milligram CSS](https://milligram.io/).

## Installation and Setup

### 1. Prerequisites
- **XAMPP** (or any local PHP server)
- **Git** (for version control)
- **VS Code** (or any code editor)

### 2. Clone the Repository
```sh
cd C:\xampp\htdocs # Navigate to XAMPP htdocs folder
git clone https://github.com/your-username/php-todo-list.git
d cd php-todo-list
```

### 3. Run the Project
1. Start **Apache** from the XAMPP Control Panel.
2. Open your browser and visit:
   ```
   http://localhost/php-todo-list/
   ```

## File Structure
```
php-todo-list/
├── task.php         # Main application file
├── tasks.json        # Stores tasks (auto-created if missing)
├── README.md         # Documentation

```

## How It Works
### 1. **Adding a Task**
- Enter a task in the input box and click **Add Task**.
- The task is stored in `tasks.json`.
- The page reloads automatically.

### 2. **Marking as Done/Undone**
- Click on a task to toggle between **completed** and **not completed**.
- A completed task has a line-through style.

### 3. **Deleting a Task**
- Click the **Delete** button next to a task to remove it.
- The task is deleted from `tasks.json`.

## Contributing
Feel free to contribute by submitting pull requests or reporting issues.



