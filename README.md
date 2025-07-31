# 🪑 Exam Seat Allocation System

A web-based system developed to automate the process of allocating seats for examinations in educational institutions. Built with the MERN stack and Python for Excel file manipulation, this system is designed to reduce administrative workload and increase accuracy and scalability.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Modules](#modules)
- [Future Scope](#future-scope)

---

## 🧩 Overview

The **Exam Seat Allocation System** provides a seamless interface for exam cell faculty to manage rooms, upload exam data, and automatically generate seat allocation plans. It aims to eliminate manual errors and optimize room usage across campus.

---

## ✨ Features

- User authentication and protected routing  
- Add/edit/delete exam halls  
- Upload student & exam details via Excel files  
- Auto-generate seat allocation reports  
- Download seat plans as Excel or PDF  
- Responsive frontend interface  
- Scalable backend logic  
- Real-time data updates using MongoDB  

---

## ⚙️ Tech Stack

**Frontend:**
- React.js  
- Tailwind CSS  
- Axios  
- React Router v6  

**Backend:**
- Node.js  
- Express.js  
- openpyxl (Python via `child_process`)  
- MongoDB  
- Mongoose  
- Cors, Nodemailer, CookieParser, Express FileUpload  

---

## 🧱 System Architecture
[ User ] ⇄ [ React JS Frontend ] ⇄ [ Node.js + Express Backend ] ⇄ [ MongoDB ]
⇓
[ openpyxl + Excel Reports ]

---
## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/exam-seat-allocation.git
   cd exam-seat-allocation
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start backend and frontend servers:**

   **Backend:**
   ```bash
   node index.js
   ```

   **Frontend:**
   ```bash
   cd client
   npm start
   ```

4. **Ensure MongoDB is running** and Python with `openpyxl` is installed.

---

## 📋 Usage

- Register/login to the system  
- Add exam halls and capacities  
- Upload student exam details (Excel)  
- Generate seat allocation for specific dates  
- Download the seat plan  

---

## 🧩 Modules

- **Login/Register** – Secure access to the system  
- **Manage Rooms** – Add, update, or delete exam halls  
- **Exam Details** – Upload & manage exam timetables and student data  
- **Seat Allocation** – Generate reports and download Excel/PDF  

---

## 🔮 Future Scope

- Seat allocation for internal assessments  
- Faculty invigilation assignment module  
- Email notifications to students with seat details
