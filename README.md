# Smart Attendance System

An AI-based smart attendance management system using face recognition, Supabase cloud database, and role-based dashboards for Faculty, Students, and Parents.

---

## Overview

This project automates attendance marking through real-time face detection and recognition.  
The system records entry and exit timings, calculates attendance statistics, and provides live updates through a modern dashboard interface.

---

## Main Features

### Face Recognition Attendance
- Real-time webcam face detection
- Automatic attendance marking
- Entry and exit tracking
- Late and absent detection
- Duplicate attendance prevention

### Role-Based Dashboards

#### Faculty Dashboard
- Start and stop attendance sessions
- Enroll students with face data
- Monitor live attendance
- View analytics and reports
- Update attendance manually

#### Student Dashboard
- View attendance records
- Check entry and exit timings
- Monitor attendance percentage
- Receive real-time updates

#### Parent Dashboard
- Track student attendance
- View late or absent alerts
- Monitor attendance history

---

## Smart Attendance Logic

- Attendance is marked automatically after face verification
- Entry and exit are recorded separately
- Students arriving late are marked accordingly
- Absentees are detected automatically
- Cooldown logic avoids multiple entries for the same person

---

## Technologies Used

### Frontend
- React
- Lovable UI
- Webcam API
- Real-time updates

### Backend
- FastAPI (Python)
- Supabase

### AI and Computer Vision
- OpenCV
- face_recognition (dlib)
- YOLO (optional advanced detection)

---

## Database Structure

### Students Table
- student_id
- name
- email
- parent_email
- face_encoding

### Attendance Table
- id
- student_id
- date
- entry_time
- exit_time
- status

---

## Supabase Integration

The project uses Supabase for:
- Authentication
- PostgreSQL database
- Real-time synchronization
- Storage management

Environment configuration:

```env, SUPABASE
