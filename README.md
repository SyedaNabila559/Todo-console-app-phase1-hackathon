# 📝 Python Console Todo App – Phase 1

A simple, interactive CLI-based Todo application built with Python, using in-memory storage.
This project is perfect for beginners who want to practice Python basics, logic building, and clean code structure.

# 🚀 Features

➕ Add Tasks – Create new todo tasks

📋 List Tasks – View all tasks with status

✅ Mark Task as Done – Complete a task

❌ Delete Task – Remove unwanted tasks

🔐 Input Validation – Handles empty input & invalid IDs

🎨 Emoji-based UI – Friendly and readable console output

# 🛠️ Requirements

Python 3.6 or higher

Works on Windows, macOS, and Linux

# 📁 Project Structure
Phase1/
├── README.md          # Project documentation
├── CLAUDE.md          # Project constitution (Spec-Driven Development)
├── specs/
│   └── phase1.md      # Phase 1 requirements
└── src/
    └── todo_app.py    # Main Python application

# ▶️ How to Run the Application
1️⃣ Check Python Installation

Open terminal / PowerShell and run:

python --version


or

python3 --version

2️⃣ Navigate to Project Folder
cd Phase1

3️⃣ Run the App
python src/todo_app.py

# 🖥️ Application Menu

When the app starts, you will see:

📝 Python Console Todo App - Phase 1 🎉

1. Add Task ➕
2. List Tasks 📋
3. Mark Task as Done ✅
4. Delete Task ❌
5. Exit 🚪

# 📌 Usage Guide
➕ Add Task

Choose option 1

Enter a task description

Empty input is not allowed

📋 List Tasks

Choose option 2

Shows all tasks with:

ID

Status (Pending / Done)

Description

✅ Mark Task as Done

Choose option 3

Enter a valid task ID

❌ Delete Task

Choose option 4

Enter a valid task ID

🚪 Exit

Choose option 5 to exit the app

🧪 Example Output
🌟 Welcome to Python Console Todo App! 🌟
===================================================
Let's manage your tasks easily and efficiently. 🙌
===================================================

📝 Enter task description: Learn Python
✅ Task added successfully! (ID: 1)

ID    Status       Description
1     🕒 Pending   Learn Python

⚠️ Error Handling

The app safely handles:

❌ Empty task descriptions

❌ Invalid menu choices

❌ Non-numeric task IDs

❌ Task ID not found errors

🧠 Technical Details

Storage: In-memory (Python list)

Task Structure:

{
  "id": int,
  "description": str,
  "done": bool
}


ID System: Auto-incrementing IDs

📌 Limitations

Data is not saved permanently

All tasks are lost when the app closes

🔮 Future Improvements (Next Phases)

💾 Persistent storage (JSON / SQLite)

📅 Due dates & reminders

🔍 Search & filter tasks

🖥️ GUI version (Tkinter)

🌐 Web version (Flask / FastAPI)

# 👨‍💻 Author

Built with ❤️by Nabila

# Great project for practice, learning & hackathons 🚀
