# 💼 MERN Stack Job Portal

A professional **Job Portal Web Application** built using the **MERN Stack (MongoDB, Express, React, Node.js)** that connects **Employers** and **Job Seekers**.  
This project demonstrates **real-world full-stack development** skills — including authentication, CRUD operations, file uploads, dynamic filtering, and responsive UI.  

> 🧠 Designed to showcase strong **frontend + backend integration** skills — perfect for portfolio and resume highlights.

---

## 🚀 Live Demo

🔗 [View Deployed App on Vercel](https://mern-job-portal-deploy.vercel.app)

> ⚠️ **Note:**  
> - Render’s free tier **automatically shuts down the app** if it hasn't been used for a while.  
>   To load the app, you may need to **refresh the page** after opening the live demo.  
> - Uploaded **images/files may be removed** due to free-tier storage limitations.

---

## 🧩 Features Overview

### 👔 Employer Dashboard
- 📊 View total active jobs, recent applicants, and hiring stats.  
- 🧾 Post new jobs with title, location, category, type, and salary.  
- 🧠 Manage job listings, view applicants, download resumes.  
- ✅ Change applicant status (Review, Accepted, Rejected).  
- 🔄 Toggle job visibility (Active/Closed).  
- 🧑‍💼 Update profile info, company name, description, and logo.

### 💼 Job Seeker Features
- 🌍 Browse all jobs without login.  
- 🔍 Filter by category, job type, location, or salary.  
- 🧰 Search by title or city (e.g., *Mumbai*, *Bangalore*).  
- 🖼️ Switch between grid or list views.  
- 🧾 Apply for jobs (after login).  
- 💾 Save/Unsave jobs for later.  
- 👤 Manage profile, upload resume & profile photo.


## 🧠 Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Frontend** | React, Tailwind CSS, Axios, React Router DOM, Framer Motion, Lucide Icons, React Hot Toast |
| **Backend** | Node.js, Express.js, MongoDB, Mongoose, Multer, JWT, bcryptjs, dotenv, CORS |
| **Deployment** | Vercel (Frontend), Render (Backend) |

<!--
## 🧑‍💼 Demo Credentials

**Employer**  
📧 `employer@demo.com`  
🔑 `123456`

**Job Seeker**  
📧 `jobseeker@demo.com`  
🔑 `123456`
-->
---

## 🖼️ Screenshots

| Employer Dashboard |
|:--------------------:|
| <img width="1600" height="812" alt="Screenshot 2025-11-05 034356" src="https://github.com/user-attachments/assets/a97542de-3cb8-4426-af61-50c3a3839973" /> |
| **Job Management** |
| <img width="1600" height="811" alt="Screenshot 2025-11-05 034512" src="https://github.com/user-attachments/assets/c243056d-6665-41e7-84e1-839edd75ecfa" />|
| **Job Seeker View** |
| <img width="1600" height="806" alt="Screenshot 2025-11-05 035447" src="https://github.com/user-attachments/assets/8adfe473-893f-4211-8f30-cac418c39650" />|

| Job Seeker Profile |
|:-------------:|
| <img width="1600" height="807" alt="image" src="https://github.com/user-attachments/assets/0a7b178d-8f99-4546-a206-d9cff9ea7096" /> |
| **Job Details** |
|<img width="1600" height="807" alt="image" src="https://github.com/user-attachments/assets/bedc8d9f-10de-4687-a218-cb5dc96e5f44" /> |
| **Saved Jobs** |
| <img width="1600" height="806" alt="image" src="https://github.com/user-attachments/assets/8ab87766-2c3d-414d-a9bc-b59868b45325" /> |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yashtank86/mern-job-portal-with-employer-and-jobseeker-dashboard.git
cd mern-job-portal-with-employer-and-jobseeker-dashboard
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```
Create a `.env` file inside `/backend`:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8000
```
Run the server:
```bash
npm start
```

### 3️⃣ Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```

Your app will be live at:  
📍 Frontend → `http://localhost:5173`  
📍 Backend → `http://localhost:8000`

---

## 🧱 Project Directory Structure

```
mern-job-portal-with-employer-and-jobseeker-dashboard/
│
├── backend/               # Node + Express Backend
│   ├── config/            # Database & JWT config
│   ├── controllers/       # Business Logic
│   ├── middleware/        # Auth Middleware
│   ├── models/            # Mongoose Models
│   ├── routes/            # API Routes
│   ├── uploads/           # User Profile Pic Storage
│   └── server.js
│
├── frontend/              # React Frontend
│   ├── src/
│   │   ├── assets/        # Static files like images, icons, fonts
│   │   ├── components/    # UI Components
│   │   ├── pages/         # Page Components
│   │   ├── context/       # Context API
│   │   ├── utils/         # Helper functions
│   │   ├── routes/        # Route configuration
│   │   └── App.jsx
│   └── package.json
│
└── README.md
```

---

## 💡 Future Enhancements
- 📈 Add analytics and charts to employer dashboard  
- 💬 Real-time chat between employer & applicant  
- 🧠 AI-powered job recommendations  
- 📩 Email alerts for new applications  

---

## ✨ Why This Project Stands Out
- ✅ Production-ready **authentication system** (JWT + bcrypt)  
- ✅ Real-world **file upload** handling (Multer)  
- ✅ Polished **frontend UX** with Tailwind and Framer Motion  
- ✅ Proper **backend architecture** with modular routes/controllers  
- ✅ Designed to demonstrate **end-to-end full-stack proficiency**

---

## ⭐ **Support**
If you like this project, don’t forget to ⭐ **star** the repository and share it!
