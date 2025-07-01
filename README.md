# Face-Recognition-Attendance-System
A Python-based facial recognition attendance system with a Tkinter GUI and SQLite database for managing student/employee attendance.

## Overview

This project implements a facial recognition-based attendance system using Python. It utilizes the face_recognition library for face detection and recognition, OpenCV for webcam capture, Tkinter for the GUI, and SQLite for storing attendance records. The system allows users to add new individuals, mark attendance via webcam, and view attendance records.

## Features
 - Add New Person: Capture a photo via webcam and store the person's details in a database.
 - Mark Attendance: Detect faces in real-time, match them against known faces, and log attendance with timestamps.
 - View Attendance: Display attendance records in a Tkinter window.
 - Database Storage: Uses SQLite to store person details and attendance logs.
 - Error Handling: Includes logging and user feedback for camera issues, missing faces, or duplicate attendance entries.
 - Matplotlib Integration: Displays the live video feed with face recognition annotations in a Tkinter window.

## Dependencies
 - Python 3.11 or higher
 - Libraries:
   - opencv-python (for webcam capture)
   - face-recognition (for face detection and recognition)
   - numpy
   - pillow (for image handling in Tkinter)
   - pandas (for displaying attendance records)
   - matplotlib (for video feed display)
   - tkinter (included with Python)
   - dlib (dependency for face-recognition)
  


## Usage
 - Launch the Application:
    - Run the notebook or the main script.
    - A Tkinter window will open with options: "Add New Person", "Start Attendance", "View
      Attendance", and "Exit".
 - Add New Person:
   - Click "Add New Person" to open a new window.
   - Enter the person's name and click "📸 Capture Photo" to take a photo via webcam.
   - Click "Submit" to save the person's details and photo to the database.
 - Mark Attendance:
   - Click "Start Attendance" to start the webcam feed.
   - The system will detect faces, match them against known faces, and mark attendance in the         database.
   - Click "Stop Attendance" to end the process.
  - View Attendance:
    - Click "View Attendance" to display all attendance records in a new window.
