# Attendance Monitoring System with GUI & Face Recognition

## Tech Stack
- Python, Tkinter, OpenCV, SQLite
- Pandas, Matplotlib

## Project Overview
A desktop application to automate attendance tracking using facial recognition. Student information and attendance are stored in a structured SQLite database, with real-time visualization and reporting.

## Features
- Register students with name, email, mobile, gender, subjects, and address (`reg.py`)
- Manage student database and CRUD operations (`sql.py`)
- Display attendance and student information through a GUI interface (`web.py`)
- Track attendance using face recognition
- Generate real-time attendance reports

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Attendance-Monitoring-System-with-GUI-Face-Recognition.git

2. Navigate to the project folder:
   cd Attendance-Monitoring-System-with-GUI-Face-Recognition
   
4. Install dependencies:
   pip install -r requirements.txt
   
6. Run the application:
   python web.py

Usage

Open the GUI application (web.py)

Register students using reg.py

Database operations handled via sql.py

Use the face recognition module to mark attendance

Generate reports for visualization
   
