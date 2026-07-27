# 🚀 Job Portal SaaS

A modern, full-stack Job Portal SaaS application that connects job seekers, recruiters, and administrators through a single platform. The application provides role-based authentication, job management, company profiles, application tracking, and an intuitive dashboard experience.

---

## 📌 Project Overview

Job Portal SaaS is designed to simplify the recruitment process by providing three dedicated portals:

- 👤 User Portal
- 🏢 Recruiter Portal
- 🛠️ Admin Portal

Users can browse and apply for jobs, recruiters can manage companies and job postings, while administrators oversee the entire platform.

---

# ✨ Features

## 👤 User

- User Registration
- User Login
- Browse Jobs
- View Job Details
- Apply for Jobs
- Track Applications
- User Dashboard
- Profile Management
- Settings

---

## 🏢 Recruiter

- Recruiter Dashboard
- Company Profile
- Post New Jobs
- Edit Jobs
- Manage Posted Jobs
- View Applicants
- Track Applications

---

## 🛠️ Admin

- Admin Dashboard
- Manage Users
- Manage Recruiters
- Manage Companies
- Manage Jobs
- Reports & Analytics

---

# 🛠️ Tech Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- Radix UI
- Wouter
- Lucide React

---

## Backend

- Node.js
- Express.js

---

## Database

- PostgreSQL

---

## Authentication

- BCrypt Password Hashing
- Role-Based Authentication

---

# 📁 Project Structure

```
job-portal-saas/

├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── contexts/
│   │   ├── hooks/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── recruiter/
│   │   │   ├── Home.tsx
│   │   │   ├── Login.tsx
│   │   │   └── Register.tsx
│   │   └── ...
│   └── public/
│
├── backend/
│   ├── config/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── server.js
│   └── .env
│
└── package.json
```

---

# 🔐 Authentication

- User Registration
- User Login
- Password Encryption using BCrypt
- PostgreSQL Database Integration
- Role-Based Access Control

---

# 👥 User Roles

### User

- Register
- Login
- Browse Jobs
- Apply Jobs
- Track Applications

### Recruiter

- Login
- Company Profile
- Post Jobs
- Manage Jobs
- View Applicants

### Admin

- Login
- Manage Users
- Manage Recruiters
- Manage Companies
- Platform Analytics

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/job-portal-saas.git
```

```
cd job-portal-saas
```

---

## Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd backend
npm install
```

---

# 🚀 Run Project

### Backend

```bash
cd backend
npm run dev
```

Runs on

```
http://localhost:5000
```

---

### Frontend

```bash
cd client
npm run dev
```

Runs on

```
http://localhost:3000
```

---

# 🗄️ Database

Database Used:

- PostgreSQL

Create a `.env` file inside the backend folder.

Example:

```env
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=your_password
DB_NAME=job_portal

PORT=5000
```

---

# 🔑 Demo Credentials

## Admin

```
Email:
admin@jobportal.com

Password:
admin@123
```

---

## Recruiter

```
Email:
recruiter@jobportal.com

Password:
recruiter@123
```

---

## User

Create a new account using the registration page.

---

# 📸 Screenshots

- Home Page
- Login
- Register
- User Dashboard
- Recruiter Dashboard
- Admin Dashboard
- Company Profile
- Job Listings

(Add screenshots here.)

---

# 🔮 Future Enhancements

- JWT Authentication
- Email Verification
- Resume Upload
- Interview Scheduling
- Notifications
- AI Resume Matching
- Real-Time Chat
- Payment Integration

---

# 👨‍💻 Developed By

**Manvitha Nalla**


---

# 📄 License

This project is developed for educational and learning purposes.
