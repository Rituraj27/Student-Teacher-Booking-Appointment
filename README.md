# Student-Teacher Booking Appointment System

This is a MERN stack project designed to facilitate the booking of appointments between students and teachers. The system includes functionalities for admins to manage teachers, for teachers to manage their appointments, and for students to book appointments with teachers.

## Table of Contents

- [Features](#features)
- [System Modules](#system-modules)
  - [Admin](#admin)
  - [Teacher](#teacher)
- [Tech-Stack-Used](#tech-stack-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Login Acess](#login)

## Features

- Admin management for adding, updating, and deleting teachers and approving student registrations.
- Teacher functionalities for managing their appointment schedules, approving/cancelling appointments, sending email alerts to students, viewing messages, and viewing all appointments.
- Student functionalities for registering, booking appointments with teachers, sending email alerts to teachers, and sending messages.

## System Modules

### Admin

- Add Teacher (Name, Department, Subject, etc.)
- Update/Delete Teacher
- Approve Registration Student

### Teacher

- Login
- Schedule Appointment
- Approve/Cancel Appointment
- Send Email Alerts to Students
- View Messages
- View All Appointments

### Student

- Register
- Login
- Book Appointment
- Send Email Alert to Teacher
- Send Message

## Tech-Stack-Used

### Frontend

![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white&style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white&style=for-the-badge)
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=for-the-badge)
![React Icons](https://img.shields.io/badge/-React_Icons-888?logo=react&logoColor=white&style=for-the-badge)
![React Router](https://img.shields.io/badge/-React_Router-CA4245?logo=reactrouter&logoColor=white&style=for-the-badge)
![React Toastify](https://img.shields.io/badge/-React_Toastify-FFDD00?logo=react&logoColor=black&style=for-the-badge)
![Axios](https://img.shields.io/badge/-Axios-5A29E4?logo=axios&logoColor=white&style=for-the-badge)

### Backend

![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=for-the-badge)
![JWT](https://img.shields.io/badge/-JWT-000000?logo=jsonwebtokens&logoColor=white&style=for-the-badge)
![Nodemailer](https://img.shields.io/badge/-Nodemailer-0079FF?logo=maildotru&logoColor=white&style=for-the-badge)
![Bcrypt](https://img.shields.io/badge/-Bcrypt-4A4A55?style=for-the-badge&logoColor=white)

### Database

![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/rituraj27/StudentTeacher-Booking-Appointment
   ```

2. **Install backend dependencies:**

   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies:**

   ```bash
   cd frontend
   npm install
   ```

4. **Set up environment variables for the backend:**

   Create a `.env` file in the `backend` directory with the following content:

   ```env
   DB_URL=''
   JWT_KEY = ''
   PORT = 5000

   # mail integration

   MAIL_HOST = smtp.gmail.com
   MAIL_USER = 'your_mail'
   MAIL_PASS =
   ```

5. **Run the backend server:**

   ```bash
   cd backend
   npm run dev
   ```

6. **Run the frontend server:**
   ```bash
   cd frontend
   npm run dev
   ```
7. **Set up environment variables for frontend:**

   Create a `.env.local` file in the `frontend` directory with the following content:

   ```env
   VITE_BACKEND_URL='http://localhost:5000'
   ```

The application should now be running on `http://localhost:5173/`.

## Usage

1. **Admin:**

   - Log in to the admin dashboard.
   - Add, update, or delete teachers.
   - Approve student registrations.

2. **Teacher:**

   - Log in to the teacher portal.
   - Schedule, approve, or cancel appointments.
   - Send email alerts to students.
   - View messages and all appointments.

3. **Student:**
   - Register and log in to the student portal.
   - Book appointments with teachers.
   - Send email alerts and messages to teachers.

## Screenshots

Landing Page

![landingpage Dark](image.png)

Teacher Dashboard

![teacher d Dark](image-1.png)

Admin Dashboard

![admin ](image-2.png)

## Login

**Student**

```bash
email: student@gmail.com
Password: pass123
```

**Teacher**

```bash
email: teacher@gmail.com
Password: pass123
```

**Admin**

```bash
email: admin@gmail.com
Password: admin
```
