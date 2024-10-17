# Kanban-Task-Management
Task Management Kanban Board
![Screenshot 2024-10-17 130121](https://github.com/user-attachments/assets/2356437d-fd60-4760-8a3e-c97d7a222140)


# Project Overview
This project is a responsive Kanban board app designed for effective task and board management. It adjusts seamlessly to different screen sizes, providing an intuitive experience whether on desktop or mobile. Users can easily manage boards, tasks, and subtasks with functionality to create, edit, remove, and organize them within columns.

# Key Features
The app allows users to:
Experience a responsive layout optimized for all device screen sizes.
Interact with hover effects on buttons and clickable items.
Add, view, update, and delete boards and tasks.
Receive validation messages during board/task creation or editing.
Mark subtasks as completed and move tasks across columns.
Toggle the visibility of the board sidebar.

# Functional Behavior
Boards:
Switching between boards via the sidebar updates the displayed board.
Clicking "Create New Board" launches a modal for adding a new board.
The "Edit Board" option in the dropdown opens a modal to modify board details.
Add or remove columns when using the Add/Edit Board modals.
Confirmations are required before deleting a board, which also deletes all its columns and tasks.

Columns:
At least one column must be present on a board before tasks can be added. The "Add New Task" button will be disabled if there are no columns.
Clicking "Add New Column" opens the "Edit Board" modal, allowing users to add columns.

Tasks:
New tasks are added at the end of the relevant column.
When updating the task's status, it is automatically moved to the correct column.

# Additional Feature:
Tasks can be moved between columns by dragging and dropping for smoother task organization.

Note ->This app enhances productivity by allowing users to manage tasks efficiently through an intuitive, flexible Kanban system with drag-and-drop support for task movement across columns.
