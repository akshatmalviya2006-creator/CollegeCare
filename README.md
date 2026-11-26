# CampusCare – Smart Complaint Management System

**IWT Mini Project | Prestige Institute of Engineering Management & Research (PIEMR)**

## About the Project

CampusCare is a simple web-based complaint management system developed as part of our Internet and Web Technology (IWT) mini-project.

The main purpose of this project is to provide students with an easy way to submit complaints related to college facilities and allow administrators to manage and resolve those complaints.

## Team Members

| Name            | Roll Number  |
| --------------- | ------------ |
| Akshat Malviya  | 0863CS241021 |
| Akshita Patidar | 0863CS241022 |

## Technologies Used

- HTML5 – Webpage structure
- CSS3 – Styling and layout
- JavaScript – Functionality and validation
- PHP – Backend processing
- MySQL – Database management

## Project Structure

```text
CampusCare/
├── index.html
├── student-login.html
├── student-register.html
├── student-dashboard.html
├── admin-login.html
├── admin-dashboard.html
├── about.html
├── style.css
├── script.js
├── database.sql
└── php/
    ├── db.php
    ├── login.php
    ├── register.php
    ├── complaint.php
    └── admin.php
```

## Features

### Student Module

- Student registration and login
- Login using email or enrollment number
- Submit complaints with title, category and description
- Select complaint priority
- Automatically generated complaint ID
- View submitted complaints
- Track complaint status
- Filter complaints by category and status
- View student profile

### Admin Module

- Admin login
- View all submitted complaints
- Update complaint status
- Delete complaints
- Search and filter complaints
- View registered students
- View complaint statistics and reports

### Other Features

- Responsive design
- Dark mode
- Form validation
- Password show/hide option
- Notification messages
- Automatic complaint timestamps

## Complaint Categories

- Electrical
- Water
- Cleanliness
- WiFi / Internet
- Classroom
- Hostel
- Others

## Complaint Status

Complaints follow three main stages:

```text
Pending → In Progress → Resolved
```

## Database

The project uses MySQL for storing application data.

Main database tables:

1. **admin** – Stores administrator login details.
2. **students** – Stores registered student information.
3. **complaints** – Stores complaints submitted by students.

The database structure and sample data are provided in `database.sql`.

## How to Run the Project

1. Install XAMPP or configure Apache, PHP and MySQL.
2. Copy the CampusCare folder into the web server directory.
3. Start Apache and MySQL.
4. Open phpMyAdmin and create a database named `campuscare`.
5. Import the `database.sql` file.
6. Configure the database connection in `php/db.php`.
7. Open the following URL in your browser:

```text
http://localhost/CampusCare/
```

## Project Objective

The objective of CampusCare is to make the college complaint process easier, faster and more organized. It provides a common platform where students can report problems and administrators can monitor and manage them.

---

**Developed by:**  
Akshat Malviya – 0863CS241021  
Akshita Patidar – 0863CS241022

**Prestige Institute of Engineering Management & Research (PIEMR)**  
**Subject: Internet and Web Technology (IWT)**
