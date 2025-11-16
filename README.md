Placement Management System

A web-based Placement Management System built using PHP and MySQL to automate and manage campus recruitment activities. It provides role-based dashboards for Admin and Students, enabling efficient management of placement drives, student registrations, applications, and notifications.

🚀 Overview

This system digitizes the complete placement workflow within an educational institution. Admins can create and manage placement drives, while students can browse drives, apply online, and track updates. The platform ensures smooth coordination, faster communication, and transparency in the recruitment process.

✨ Key Features
🔹 Admin Features

Add, update, and delete placement drives

View registered students & applications

Post announcements and updates

Manage company details and job roles

Dashboard with overview of activities

🔹 Student Features

Register & log in securely

View latest placement drives

Apply for available drives

Check application status

View announcements & updates

🔹 General Features

Responsive UI using HTML/CSS

Clean database structure

Organized directory for drives

Email/notification support

Easy-to-use interface for all users

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Server: XAMPP / WAMP / LAMP

📂 Project Structure
Placement-Management-System/
│── admin dash.PNG
│── student dash.PNG
│── placement home.PNG
│── placement latest.PNG
│── placement drive.PNG
│── README.md
│
├── Database/
│   └── placement.sql
│
├── Drives/
│   ├── index.php
│   ├── 1.php
│   ├── 2.php
│   ├── 3.php
│   ├── mail.php
│   ├── blog.php
│   ├── 404.php
│   ├── css/
│   └── images/

▶️ How to Run the Project

Download or Clone the Repository

git clone <repository-url>


Move the project folder to your server directory:

XAMPP → htdocs/

WAMP → www/

Setup the Database

Open phpMyAdmin

Create a database (e.g., placement_db)

Import the file:

Database/placement.sql


Configure Database Connection

Update DB credentials inside the PHP configuration files (if required).

Run the Project

Start Apache & MySQL

Open in browser:

http://localhost/Placement-Management-System/

🔮 Future Enhancements

Admin analytics dashboard

Resume upload & screening

Company login module

Email & SMS alert system

Student performance tracking

Export reports (PDF/Excel)

📘 Conclusion

The Placement Management System provides a streamlined digital solution for managing campus recruitment activities. With easy navigation and essential features for both admin and students, the system improves efficiency, organization, and communication throughout the placement process.
