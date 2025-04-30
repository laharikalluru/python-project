# python-project

# 🧠 Virtual Assistant for Time Management

## 📌 Overview

This project is a **Virtual Assistant for Time Management** built using Python. It is designed to help users, especially students, stay organized by managing their **daily tasks**, **class schedules**, and **reminders** through a simple and interactive graphical user interface (GUI).

The assistant uses **text-to-speech** technology to read out reminders and schedules, and stores task-related data using CSV files. It is completely **offline**, easy to use, and ideal for improving personal productivity.

---

## 🛠️ Features

- ✅ Add and view tasks
- 🏫 Manage and view class schedules
- ⏰ Set voice reminders
- 📊 Check productivity stats
- 🎙️ Hear your reminders with speech output
- 🖥️ Built-in GUI for user-friendly interaction

---

## ⚙️ How It Works

1. When the program starts, a **Tkinter GUI** window opens.
2. The user can:
   - Add tasks to a to-do list
   - View today's class schedule
   - Receive reminders at specific times
3. The assistant uses the **current date and time** to check if there are any pending reminders or schedules.
4. It reads the content from CSV files where all the tasks and schedules are stored.
5. If a reminder is due, the assistant will **speak the message** using `pyttsx3` library.

---

## 🧰 Libraries Used and Their Purpose

| Library       | Purpose |
|---------------|---------|
| `tkinter`     | To create the GUI for user interaction |
| `csv`         | To read and write task and schedule data from CSV files |
| `pyttsx3`     | To convert text to speech for voice reminders |
| `datetime`    | To fetch and compare the current date and time for task/schedule matching |
| `time`        | To create delays or check for upcoming reminders |
| `os`          | To handle file paths and file system operations |

---

## 🎯 Purpose of the Project

The main purpose of this virtual assistant is to:

- Help users **organize their tasks and schedules**
- Provide **audio-based reminders** to improve focus
- Offer a simple **offline tool** for time and task management
- Serve as a mini personal assistant for students and busy individuals

---

## ▶️ How to Run the Project

1. Install Python 3.x
2. Install the required library:
   ```bash
   pip install pyttsx3

## Run the application

python main.py

## File Structure
virtual_assistant/
│
├── main.py              # Main program file
├── tasks.csv            # Stores task entries
├── schedule.csv         # Stores class schedules
└── README.md            # Documentation
