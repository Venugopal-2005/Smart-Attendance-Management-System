# Smart Attendance Management System

An AI-powered Smart Attendance Management System that automates student attendance using **Face Recognition** and **Computer Vision**. The system eliminates manual attendance, improves accuracy, and provides an efficient solution for educational institutions and organizations.

---

## Features

- AI-powered face recognition for attendance
- Real-time face detection and identification
- Automatic attendance recording
- User-friendly web interface
- Secure authentication
- Attendance history and reports
- Fast and accurate attendance processing
- Reduces manual attendance effort by approximately 90%

---

## Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- FastAPI
- Python

### AI & Computer Vision
- OpenCV
- Face Recognition

### Database
- PostgreSQL / Supabase

### Tools
- Git
- GitHub
- Docker

---

## Project Architecture

```
Frontend (React)
        │
        ▼
FastAPI Backend
        │
        ▼
Face Recognition Engine
(OpenCV + Face Recognition)
        │
        ▼
Attendance Database
(PostgreSQL / Supabase)
```

---

## Workflow

1. User logs into the system.
2. Camera captures live video.
3. Face is detected using OpenCV.
4. Face is matched with registered users.
5. Attendance is automatically marked.
6. Attendance is stored in the database.
7. Reports can be viewed through the dashboard.

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Venugopal-2005/Smart-Attendance-Management-System.git
```

### Navigate to the project

```bash
cd Smart-Attendance-Management-System
```

### Install backend dependencies

```bash
pip install -r requirements.txt
```

### Install frontend dependencies

```bash
npm install
```

### Run the backend

```bash
uvicorn main:app --reload
```

### Run the frontend

```bash
npm start
```

---

## Screenshots

> Add screenshots here

Example:

- Login Page
- Registration Page
- Face Detection
- Attendance Dashboard

---

## Future Improvements

- Multi-camera attendance
- Anti-spoofing (liveness detection)
- Mobile application
- Cloud deployment
- Email notifications
- Attendance analytics dashboard

---

## Project Highlights

- AI-powered attendance automation
- Real-time face recognition
- Computer Vision-based solution
- Modern React + FastAPI architecture
- Scalable and efficient system

---

## Author

**Venugopal K**

- LinkedIn: https://www.linkedin.com/in/venugopal-k-0bba49287
- GitHub: https://github.com/Venugopal-2005

---

## License

This project is developed for educational and learning purposes.
