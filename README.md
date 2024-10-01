# To Do App

This is a simple To Do application where users can manage their tasks efficiently. Users can add new tasks, mark tasks as completed, and filter tasks based on their status (To Do, Pending, or Completed). It also displays a counter of pending tasks.

All modifications made within the app (like adding tasks or marking them as completed) are stored in the browser's local storage. To revert the app to its initial state, follow these steps:

- Right-click anywhere on the app -> **Inspect** -> **Application** -> **Local Storage** -> Delete the "state" entry (this is where all the modifications are stored).

## Features

- **Add Tasks**: Users can input their tasks in the provided text box, and it will appear in the task list.
- **Task Status**: Tasks can be marked as completed by clicking the circle on the left side of the task, striking through the task.
- **Pending Tasks Counter**: A counter is displayed showing how many tasks are still pending.
- **Tabs to Filter Tasks**:
  - **To Do**: Displays all tasks (both pending and completed).
  - **Pending**: Displays only the pending tasks (not strikethrough).
  - **Completed**: Displays only the completed (strikethrough) tasks.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vlicus/todo-app.git
2. Navigate to the project directory:
   ```bash
   cd todo-app

4. Install the necessary dependencies:
   ```bash
   npm install

6. Run the app locally:
   ```bash
   npm run dev

8. Open your browser and go to:
   http://localhost:3000
   
## Demo
You can view the deployed version of this To Do app on GitHub Pages:
[Demo](https://vlicus.github.io/todo-app/)

## How to Use

1. **Add a Task**: Enter a task in the input box and hit Enter or click the Add button. The task will appear in the list.
   
2. **Mark as Completed**: Click the circle next to a task to mark it as completed. The task will be strikethrough and moved to the Completed tab.

3. **Filter Tasks**: Use the tabs to filter between:
   - **To Do**: Shows all tasks.
   - **Pending**: Shows only tasks that haven't been completed.
   - **Completed**: Shows tasks that have been marked as completed.

4. **Pending Tasks Counter**: Shows how many tasks are left to be completed in the Pending tab.
