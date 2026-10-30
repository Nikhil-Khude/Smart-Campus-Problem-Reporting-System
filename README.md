# 🏫 Smart Campus Problem Reporting System

<p align="center">
  <b>Report • Track • Resolve</b>
  <br/>
  A smarter and more organized way to manage campus problems.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Full--Stack%20Web%20Application-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Team-Tech%20Titans-purple?style=for-the-badge"/>
</p>

---

## 📌 About The Project

**Smart Campus Problem Reporting System** is a web-based application developed to make campus problem reporting, management, and tracking easier and more transparent.

The platform provides a centralized system where students can report campus-related issues such as damaged infrastructure, cleanliness problems, water leakage, electrical faults, and other maintenance issues.

Administrators can review reports, categorize problems, assign tasks to workers, and monitor their progress until resolution.

## 🎯 Project Objectives

- Provide a centralized platform for campus problem reporting.
- Simplify the complaint submission and tracking process.
- Improve communication between students, administrators, and workers.
- Monitor problem resolution deadlines.
- Identify and escalate overdue problems.
- Maintain organized records of users and reported problems.

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 Authentication | Secure login and role-based access |
| 📝 Problem Reporting | Submit campus-related problems |
| 📸 Image Upload | Attach images as problem evidence |
| 🗂️ Categorization | Organize problems by category and subcategory |
| ⚡ Severity Classification | Identify problem priority |
| 📊 Admin Dashboard | Manage, search, and filter reports |
| 👷 Worker Assignment | Assign reported problems to workers |
| 📈 Progress Tracking | Monitor task and problem status |
| ⏱️ Overdue Detection | Identify problems exceeding deadlines |
| 🚨 Escalation | Forward unresolved problems to higher authority |
| 📧 Email Notifications | Notify students when problems are resolved |

## 👥 User Roles

- **Student:** Submit problems and track their status.
- **Admin:** Manage reports, assign workers, and monitor progress.
- **Worker:** View assigned tasks and update work progress.
- **Higher Authority:** Review escalated problems.

## 🔄 How It Works

1. Student or administrator logs into the application.
2. A campus problem is submitted with its details and images.
3. The administrator reviews and categorizes the report.
4. The administrator assigns the problem to a worker.
5. The worker updates the progress of the assigned task.
6. The system monitors the resolution deadline and overdue problems.
7. Unresolved problems can be escalated to higher authority.
8. Once resolved, an email notification is sent to the student.

## 🛠️ Technology Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**Backend**
- Python
- Flask

**Database**
- MySQL

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,flask,mysql" />
</p>

## 🗄️ Database Design

The proposed database includes the following entities:

- USER
- CATEGORY
- PROBLEM_REPORT
- REPORT_IMAGE
- WORKER_ASSIGNMENT
- ESCALATION_RECORD
- EMAIL_NOTIFICATION

The database is designed to maintain relationships between users, reports, categories, worker assignments, escalations, and notifications.

## 📂 Project Structure

```text
Smart-Campus-Problem-Reporting-System/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── images/
│
├── backend/
│   ├── app.py
│   ├── routes/
│   └── models/
│
├── database/
│   └── schema.sql
│
├── uploads/
│
├── docs/
│   └── ERD/
│
└── README.md
```

*Proposed structure; actual folders may vary during development.*

## 🚧 Project Status

<p>
  <img src="https://img.shields.io/badge/Development-Under%20Progress-orange?style=flat-square"/>
</p>

This project is currently under development as part of the FY MCA Capstone Team Project.

## 👨‍💻 Team Tech Titans

| Name | Role |
|---|---|
| **Nikhil Khude** | Team Leader |
| **Pratik Maske** | Core Team Member |

**Group:** 61  
**Course:** FY MCA  
**Institution:** MES IMCC, Pune  
**Academic Year:** 2026–2028

---

<p align="center">
  <b>🚀 Building a Smarter Campus, One Report at a Time.</b>
  <br/>
  <i>Designed and developed with ❤️ by Team Tech Titans.</i>
</p>
