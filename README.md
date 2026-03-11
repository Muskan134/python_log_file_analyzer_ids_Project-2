## 🛡 Log File Analyzer for Intrusion Detection

## 📌 Project Overview

The Log File Analyzer is a Python-based cybersecurity project designed to detect suspicious login activities from a system log file.

This tool scans a log file, identifies multiple failed login attempts, and flags IP addresses that exceed a predefined threshold. 
It also generates a structured CSV incident report for further analysis.

---

## 🎯 Features

- Detects multiple failed login attempts
- Identifies suspicious IP addresses
- Threshold-based brute-force detection
- Simple and beginner-friendly implementation

---

## 🛠 Technologies Used

- Python
- File Handling
- Dictionary Data Structure

---

## 📂 Project Structure

Cyber_projects/
│
├── log_file_analyzer.py
├── sample.log
└── README.md

---

## ▶ How to Run the Project

1. Make sure Python is installed on your system.
2. Keep `sample.log` in the same folder as `log_file_analyzer.py`.
3. Open terminal in the project folder.
4. Run the following command:

python log_file_analyzer.py

---

## 📊 Output

- Suspicious IP addresses will be displayed in the terminal.
- A file named `incident_report.csv` will be generated automatically.

---

## 🔐 Cybersecurity Concept Used

This project demonstrates a basic Intrusion Detection System (IDS) concept by identifying brute-force login attempts through log analysis.

---

## 🚀 Future Improvements

- Real-time log monitoring
- Graph visualization of attack patterns
- IP blacklist integration
- Email alert system

---

## 👩‍💻 Author

Muskan Kumari 
Cyber Security Intern



