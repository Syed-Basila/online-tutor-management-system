# 📚 Online Tutoring Management System

A comprehensive web-based platform designed to streamline the online tutoring experience by automating session scheduling, billing, student management, and report card generation.

---

## 🚀 Features

- 🔐 **User Authentication**  
  Secure login system for both students and tutors.

- 📅 **Session Scheduling**  
  Automated scheduling based on tutor availability and student preferences.

- 💳 **Billing & Payments**  
  Integrated invoicing and secure online payment processing.

- 🎓 **Student Management**  
  Efficient tracking of student profiles, sessions, and academic progress.

- 📊 **Report Card Generation**  
  Automated performance-based academic reports.

- 🛠 **Admin Dashboard**  
  Centralized panel for monitoring sessions, users, and payments.

---

## 🛠 Tech Stack

| Category     | Technology               |
|--------------|---------------------------|
| Frontend     | HTML, CSS, JavaScript     |
| Backend      | PHP                       |
| Database     | MySQL                     |
| Server       | Apache / XAMPP / WAMP     |

---

## 📁 Folder Structure

/online-tutoring-system/ │ ├── /assets/ # CSS, JS, Images ├── /includes/ # Database connection, functions ├── /pages/ # Login, Dashboard, Profile, Reports ├── /admin/ # Admin panel files ├── /students/ # Student dashboard ├── /tutors/ # Tutor dashboard ├── config.php # Database config ├── index.php # Entry point └── README.md # Project documentation



---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/online-tutoring-system.git

2.**Import Database**

Import the provided SQL file (database.sql) into your MySQL server.

3.**Configure Database**

Open config.php and update your DB credentials:
```
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "tutoring_db";
```

4.**Run Locally**

- Use XAMPP/WAMP and place the project folder inside the /htdocs directory.

- Navigate to http://localhost/online-tutoring-system/ in your browser.

