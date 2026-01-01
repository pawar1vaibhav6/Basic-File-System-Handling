# 🗂️ Directory Monitoring Script

A simple Python project that continuously monitors a specified directory and logs any file changes — including when files are **added**, **modified**, or **deleted**.

---

## 🚀 Features
- Detects new files created in the directory  
- Tracks modifications to existing files  
- Identifies deleted or missing files  
- Logs all events with timestamps for easy tracking  

---

## 🧠 What I Learned
- File and directory handling using the `os` module  
- Working with `datetime` for time-based event logging  
- Implementing structured logging for automation tasks  

---

## ⚙️ Technologies Used
- **Python 3**
- `os` module
- `datetime` module
- `logging` module

---

## ▶️ How to Run

1. Clone this repository:
```bash
    git clone https://github.com/pawar1vaibhav6/Basic-File-System-Handling.git
```

2. Navigate to the project directory:
```bash
    cd File Monitoring
```

3. Run the Python script:
```bash
    File_Monitoring_System.py
```
4. Modify or create files inside the monitored folder — changes will be logged automatically!

--------
📁 Example Log Output
```bash
    2025-11-10 21:23:24,770:__main__:INFO:text2.txt Modified
    2025-11-10 21:23:24,771:__main__:INFO:text3.txt Deleted
```
-----


