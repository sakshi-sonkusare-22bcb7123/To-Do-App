# 🛤️ Java Swing To-Do List Application – Task 6 (August 2025)

In this project, I built a **desktop To-Do List application** in Java using **Swing** and **AWT**.  
The goal was to create a simple yet effective task manager that allows users to **add, view, and delete tasks**, while saving all tasks to a local file so that the list persists across sessions.

---

## 🦕 What’s Inside?

This project includes:
- A **GUI-based task manager** with an interactive interface  
- **Add Task** functionality with instant update to the list  
- **Delete Task** option with error handling if no task is selected  
- **Persistent storage** using a `tasks.txt` file (auto-saves after every change)  
- A **clean layout** with top, center, and bottom panels  

---

## 🪼 Core Features Covered

### ✏️ Task Management
- Add tasks using the input field + **Add Task** button  
- Delete tasks by selecting from the list + **Delete Task** button  
- Real-time updates to the task list  

### 💾 Persistent Data Storage
- Reads existing tasks from `tasks.txt` on startup  
- Saves changes automatically to `tasks.txt` whenever a task is added or deleted  
- Handles file errors gracefully with dialog messages  

### 🖼 GUI Layout & Design
- **Top Panel** → `JTextField` for input + `JButton` for adding tasks  
- **Center Panel** → `JList` inside a scrollable panel for task display  
- **Bottom Panel** → `JButton` for deleting tasks  
- Error prompts and confirmations shown using `JOptionPane`  

---

## 👽 Tech Stack

| Tool / Library             | Purpose |
|----------------------------|---------|
| **Java (JDK 16+)**         | Programming language |
| **Swing (javax.swing)**    | GUI components (`JFrame`, `JPanel`, `JButton`, `JList`, etc.) |
| **AWT (java.awt)**         | Layout managers (`BorderLayout`, `FlowLayout`) |
| **File I/O (java.io)**     | Persistent storage with `BufferedReader` & `BufferedWriter` |
| **VS Code / IntelliJ IDEA**| Development environment |

---

## 🐲 What I Learned

Building this To-Do List App helped me:
- Design **user-friendly GUIs** with Swing and layout managers.  
- Use **event-driven programming** with `ActionListener` for interactive features.  
- Implement **file persistence** to maintain user data across sessions.  
- Handle **edge cases** like empty input fields or no selection during deletion.  
- Organize Swing components into panels for cleaner and more modular UI design.  

---

## 🚴‍♀️ How to Run

1. Ensure you have Java (JDK 16 or later) installed.  
2. Save the project files (`ToDoApp.java` and `tasks.txt`) in the same directory.  
   - If `tasks.txt` does not exist, the program will create one automatically.  
3. Compile the code:  
   ```sh
   javac ToDoApp.java
   ````

4. Run the application:

   ```sh
   java ToDoApp
   ```
5. Start adding and managing your tasks 🎉

---

## 🥤🍀 About the Author

**Sakshi Bhojraj Sonkusare**

Aspiring software developer passionate about building user-friendly applications and learning through hands-on projects. Always curious to explore how **GUI design** and **data persistence** can make applications more useful.

* LinkedIn: [https://www.linkedin.com/in/sakshi-sonkusare-381362354/](https://www.linkedin.com/in/sakshi-sonkusare-381362354/)
* Portfolio: Coming Soon

---

## Contributions and Support ❤️

Feedback, suggestions, and contributions are always welcome.
Pull requests for improvements, bug fixes, or feature additions are encouraged.

---
