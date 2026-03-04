# 📚 Online Examination System — ACS College, Sonai

> A secure, browser-based MCQ examination portal for students and administrators, built for Arts, Commerce & Science College, Sonai (Savitribai Phule Pune University).

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge)

---

## 📖 About

**Online Examination System** is a fully frontend, no-backend exam portal that allows students to register, log in, and attempt MCQ-based exams with auto-timers — while admins can manage students, exams, and questions through a dedicated dashboard. All data is stored locally in the browser using `localStorage`.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎓 **Student Portal** | Register, log in, and take timed MCQ exams |
| 👨‍💼 **Admin Dashboard** | Manage students, create exams and add questions |
| ⏱️ **Auto Timer** | Countdown timer per exam with auto-submission |
| 📊 **Instant Results** | Scores calculated and displayed immediately after submission |
| 💾 **Persistent Storage** | All data saved in `localStorage` — no backend needed |
| 🔒 **Session Management** | Secure login sessions via `sessionStorage` |
| 📱 **Responsive Design** | Mobile-friendly UI with hamburger navigation |

---

## 🗂️ Project Structure

```
OnlineExamSystem/
│
├── index.html                  # Home / Landing page
│
├── pages/
│   ├── student-login.html      # Student login page
│   ├── student-register.html   # Student registration page
│   ├── student-dashboard.html  # Student exam portal
│   ├── admin-login.html        # Admin login page
│   ├── admin-dashboard.html    # Admin control panel
│   └── about.html              # About page
│
├── css/
│   └── styles.css              # Global stylesheet
│
└── js/
    └── shared.js               # Shared app state, storage, utilities
```

---

## 🚀 Getting Started

No installation or server required — runs entirely in the browser.

**1. Clone the repository**
```bash
git clone https://github.com/your-username/online-exam-system.git
cd online-exam-system
```

**2. Open in browser**
```bash
# Open the home page directly
open index.html
```

> ✅ Works best on **Google Chrome** or **Microsoft Edge**

---

## 🔐 Default Credentials

### Admin
| Field | Value |
|---|---|
| Username | `admin` |
| Password | `admin123` |

### Sample Students
| Roll No | Name | Password |
|---|---|---|
| `001` | Tagadkar Mayur Sanjay | `mayur123` |
| `002` | Dahatonde Aniket Sanjay | `aniket123` |

> ⚠️ These credentials are for demo purposes only. Change them before any production use.

---

## 🧠 Sample Exam Data

Two sample exams are pre-loaded:

- **DBMS Mid Term** — 30 min, 10 marks (SQL, database models)
- **Java Programming Final** — 45 min, 15 marks (OOP, Java basics)

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure & layout |
| **CSS3** | Styling, animations, responsive design |
| **Vanilla JavaScript** | App logic, state management |
| **localStorage** | Persistent data storage (students, exams, results) |
| **sessionStorage** | Active login session tracking |
| **Google Fonts** | Plus Jakarta Sans & JetBrains Mono |

---

## 📄 Pages Overview

- **Home (`index.html`)** — Welcome page with login options and feature overview
- **Student Login** — Authenticate using Roll Number & Password
- **Student Register** — New student sign-up with form validation
- **Student Dashboard** — View available exams, take exams, see results
- **Admin Login** — Admin-only access with hardcoded credentials
- **Admin Dashboard** — Add/manage students, exams, and questions
- **About** — Project and team information

---

## 👥 Creators

<table>
  <tr>
    <td align="center">
      <b>Tagadkar Mayur Sanjay</b><br/>
      <sub>Co-Developer</sub>
    </td>
    <td align="center">
      <b>Dahatonde Aniket Sanjay</b><br/>
      <sub>Co-Developer</sub>
    </td>
  </tr>
</table>

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

<div align="center">
  <p>Made with ❤️ by <strong>Mayur</strong> & <strong>Aniket</strong></p>
  <p>© 2025 Online Exam System · ACS College, Sonai · SPPU</p>
</div>
