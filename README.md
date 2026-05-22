# ✅ TO DO LIST MANAGEMENT SYSTEM

A simple and efficient To-Do List Management System developed using C++ with Object-Oriented Programming concepts. The application helps users manage personal, work, and shopping tasks with features like task creation, updating, deletion, searching, file handling, and exception handling.

---

# 📌 Features

✅ Add new tasks  
✅ Update task details  
✅ Delete tasks  
✅ Mark tasks as completed  
✅ Search tasks by category or deadline  
✅ File handling for task storage  
✅ Exception handling support  
✅ Interactive user interface  
✅ Object-Oriented Programming implementation

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| C++ | Core Programming |
| OOP Concepts | System Design |
| File Handling | Data Storage |
| Exception Handling | Error Management |

---

# 📚 OOP Concepts Implemented

## 🔹 Inheritance
Different task types inherit from the base `Task` class.

## 🔹 Polymorphism
Virtual functions are used to display task-specific details.

## 🔹 Dynamic Binding
Overridden methods are called dynamically during runtime.

## 🔹 Encapsulation
Task data and methods are organized within classes.

## 🔹 Abstraction
Complex task operations are simplified through class structures.

---

# 📂 Task Categories

- Personal Tasks
- Work Tasks
- Shopping Tasks

---

# ⚙️ Functionalities

## ➕ Add Task
Users can create tasks with:
- Task Name
- Priority
- Deadline
- Category

---

## ✏️ Update Task
Modify:
- Priority
- Deadline
- Task Details

---

## ❌ Delete Task
Remove tasks from the system.

---

## ✅ Mark as Completed
Track finished tasks efficiently.

---

## 🔍 Search Task
Search tasks using:
- Category
- Deadline

---

# 💾 File Handling

## Input File
Reads task data from a text file.

## Output File
Stores task details in a text file for permanent storage.

---

# ⚠️ Exception Handling

The system uses `runtime_error` exceptions for:

- Task not found
- File opening failure
- Invalid operations

Example:

```cpp
throw runtime_error("Task not found");
