🏥 Elderly Care Residence Management & Emergency Support Platform

A comprehensive web-based platform designed to manage elderly care residences with health monitoring, meal management, emergency support, and financial transparency.

This system helps administrators, caregivers, and residents manage daily activities while ensuring safety, healthcare tracking, and efficient communication.

✨ Key Features
🔐 Authentication System

👤 Role-based login (Elderly User / Admin)

🔑 Secure session management

🔄 Automatic role-based dashboard redirection

👴 Elderly User Dashboard

Residents can easily manage their daily health and services.

❤️ Update daily health information
(Sugar level, Blood Pressure, Overall Condition)

🍽️ Select meals for:

Breakfast

Lunch

Snacks

Dinner

📊 View health history

🍱 View meal history

🚨 Emergency Alert Button (24/7 support)

💰 View account balance

🖥️ Admin / Management Dashboard

Administrators can monitor all residents and services.

📋 View daily health updates

🍽️ Monitor meal selections

🏠 Manage resident list with room numbers

🚨 Handle emergency alerts

💳 View financial summaries

📈 Generate monthly reports

📊 View resident statistics & analytics

👥 Resident Management

Store and manage resident data efficiently.

👤 Resident profile:

Name

Age

Photo

Room number

🏥 Medical information:

Diabetes

Blood pressure

Allergies

📅 Daily health logs

💊 Medicine schedule tracking

🍽️ Food & Kitchen Management

Meals are automatically grouped based on dietary requirements.

Diet categories include:

🩺 Diabetes-friendly

🧂 Low-salt

🥣 Soft food

❤️ Heart patient diet

Other features:

📅 Daily meal plans

📆 Weekly meal planning

📊 Meal history tracking

🚨 Emergency Support System

Ensuring quick response during emergencies.

🔴 Emergency button for each resident

⏱️ Emergency logs with timestamp & room number

🧑‍⚕️ Admin response tracking

📜 Emergency incident history

💰 Financial Transparency

Transparent financial tracking for residents and families.

💳 Resident account management

💵 Multiple payment methods:

Card

bKash

Rocket

Cash

📥 Deposit tracking

📤 Withdrawal tracking

📊 Monthly financial reports

👨‍👩‍👧 Family view-only access

⭐ Premium Services

Premium care package for additional services.

💎 Premium Package Price: ৳10,000 BDT

Benefits

🩺 Extra medical checkups

🚑 Priority medical response

👩‍⚕️ Private caregiver

🍱 Special meals

💰 Billing automatically adjusts when premium service is activated.

⭐ Rating & Feedback System

Residents can rate services to maintain quality.

🍽️ Food service rating

🧹 Cleanliness rating

🏥 Medical care rating

📊 Automatic ranking calculation

📝 Feedback tracking

📊 Health Tracking & Reports

The system continuously tracks resident health data.

Daily tracking includes:

🛌 Sleep time

💊 Medicine intake

🩸 Sugar level

❤️ Blood pressure

Reports include:

📈 Health improvement history

📅 Monthly reports per resident

🛠 Technology Stack
Layer	Technology
🎨 Frontend	HTML5, CSS3, JavaScript
⚙️ Backend	PHP 7.4+
🗄 Database	MySQL 5.7+
🌐 Server	Apache / Nginx
⚙️ Installation Guide
📌 Prerequisites

Make sure the following are installed:

PHP 7.4 or higher

MySQL 5.7 or higher

Apache / Nginx

PHP Extensions:

mysqli

pdo_mysql

mbstring

📥 Setup Steps
1️⃣ Download or Clone the Project

Place project files inside your web server directory.

Example:

XAMPP → C:\xampp\htdocs\elderly_care
WAMP  → C:\wamp64\www\elderly_care
2️⃣ Create Database

Import database schema:

mysql -u root -p < database/schema.sql

Or import database/schema.sql via phpMyAdmin.

3️⃣ Configure Database Connection

Edit:

config/database.php

Update credentials:

define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'elderly_care_db');
4️⃣ Configure Site URL

Edit:

config/config.php
define('SITE_URL', 'http://localhost/elderly_care');
5️⃣ Set Folder Permissions

Make sure the image folder is writable:

chmod 755 assets/images
6️⃣ Access the Application

Open browser:

http://localhost/elderly_care

or

http://localhost/elderly_care/index.php
🔑 Default Login Credentials
👨‍💼 Admin
Field	Value
Username	admin
Password	admin123
👴 Elderly User
Field	Value
Username	elderly1
Password	elderly123

⚠️ Important: Change these credentials in production.

📁 Project Structure
elderly_care/
│
├── config/
│   ├── config.php
│   └── database.php
│
├── css/
│   ├── style.css
│   └── admin.css
│
├── js/
│   ├── main.js
│   ├── dashboard_elderly.js
│   └── dashboard_admin.js
│
├── php/
│   ├── login.php
│   ├── logout.php
│   ├── update_health.php
│   ├── submit_meals.php
│   ├── emergency.php
│   ├── get_health_history.php
│   ├── get_meal_history.php
│   ├── get_meal_plans.php
│   └── admin/
│       ├── respond_emergency.php
│       └── generate_report.php
│
├── pages/
│   ├── home.php
│   ├── login.php
│   ├── about.php
│   ├── services.php
│   ├── contact.php
│   └── admin/
│       ├── overview.php
│       ├── residents.php
│       ├── health.php
│       ├── meals.php
│       ├── emergencies.php
│       ├── finance.php
│       └── reports.php
│
├── database/
│   └── schema.sql
│
├── assets/
│   └── images/
│
├── index.php
├── dashboard_elderly.php
├── dashboard_admin.php
└── README.md
🔒 Security Notes

For production deployment:

🔐 Use password_hash() for passwords

🛡️ Prevent SQL Injection using prepared statements

🧹 Escape output using htmlspecialchars()

🔑 Secure PHP sessions

📁 Validate uploaded files

🚀 Future Enhancements

Planned improvements:

📄 PDF report generation

📧 Email notifications

📱 SMS emergency alerts

📲 Mobile application

💬 Real-time chat support

📅 Appointment scheduling

⏰ Medication reminders

👨‍👩‍👧 Family member portal

📜 License

This project is developed for academic and educational purposes.

🙌 Credits

Developed using:

HTML

CSS

JavaScript

PHP

MySQL

✨ Academic Full-Stack Web Development Project
