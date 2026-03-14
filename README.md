# 🏥 Elderly Care Residence Management & Emergency Support Platform

A **comprehensive web-based platform** designed to manage elderly care residences with **health monitoring, meal management, emergency support, and financial transparency**.

This system helps **administrators, caregivers, and residents** manage daily activities while ensuring **safety, healthcare tracking, and efficient communication**.

---

# ✨ Key Features

## 🔐 Authentication System
- 👤 Role-based login (**Elderly User / Admin**)
- 🔑 Secure session management
- 🔄 Role-based redirection after login

---

## 👴 Elderly User Dashboard

Residents can manage their daily health and services.

- ❤️ Update daily health information (Sugar level, Blood Pressure, Overall Condition)
- 🍽️ Select meals for breakfast, lunch, snacks, and dinner
- 📊 View health history
- 🍱 View meal history
- 🚨 Emergency alert button (24/7 support)
- 💰 View account balance

---

## 🖥️ Admin / Management Dashboard

Administrators can monitor residents and services.

- 📋 View today's health updates
- 🍽️ Monitor meal selections
- 🏠 Manage resident list with room numbers
- 🚨 Handle emergency alerts
- 💳 View financial summaries
- 📈 Generate monthly reports
- 📊 View resident statistics and analytics

---

# 👥 Resident Management

- 👤 Resident information (Name, Age, Photo, Room Number)
- 🏥 Medical conditions (Diabetes, Blood Pressure, Allergies)
- 📅 Daily health logs
- 💊 Medicine schedule tracking

---

# 🍽️ Food & Kitchen Management

Meals are automatically grouped based on dietary requirements.

Diet categories:

- 🩺 Diabetes-friendly
- 🧂 Low-salt
- 🥣 Soft food
- ❤️ Heart patient diet

Other features:

- 📅 Daily meal plans
- 📆 Weekly meal plans
- 📊 Meal history tracking

---

# 🚨 Emergency Support System

- 🔴 Emergency button for residents
- ⏱️ Emergency logs with timestamp and room number
- 🧑‍⚕️ Admin response tracking
- 📜 Emergency incident history

---

# 💰 Financial Transparency

- 💳 Resident account management
- 💵 Multiple payment methods (Card, bKash, Rocket, Cash)
- 📥 Deposit tracking
- 📤 Withdrawal tracking
- 📊 Monthly financial reports
- 👨‍👩‍👧 View-only access for family members

---

# ⭐ Premium Services

💎 **Premium Package Price:** `৳10,000 BDT`

Benefits:

- 🩺 Extra medical checkups
- 🚑 Priority medical response
- 👩‍⚕️ Private caregiver
- 🍱 Special meals

Billing automatically adjusts when premium service is activated.

---

# ⭐ Rating & Feedback

Residents can rate services:

- 🍽️ Food service
- 🧹 Cleanliness
- 🏥 Medical care
- 📊 Automatic ranking calculation
- 📝 Feedback tracking

---

# 📊 Health Tracking & Reports

Daily tracking includes:

- 🛌 Sleep time
- 💊 Medicine intake
- 🩸 Sugar level
- ❤️ Blood pressure

Reports include:

- 📈 Health improvement history
- 📅 Monthly reports per resident

---

# 🛠 Technology Stack

| Layer | Technology |
|------|-------------|
| 🎨 Frontend | HTML5, CSS3, JavaScript |
| ⚙️ Backend | PHP 7.4+ |
| 🗄 Database | MySQL 5.7+ |
| 🌐 Server | Apache / Nginx |

---

# ⚙️ Installation Guide

## 📌 Prerequisites

- PHP **7.4+**
- MySQL **5.7+**
- Apache / Nginx
- PHP extensions: `mysqli`, `pdo_mysql`, `mbstring`

---

# 📥 Setup Steps

## 1️⃣ Download or Clone Project

Place project inside web server directory.

Example:

XAMPP → `C:\xampp\htdocs\elderly_care`  
WAMP → `C:\wamp64\www\elderly_care`

---

## 2️⃣ Create Database

Import database schema:

```bash
mysql -u root -p < database/schema.sql
```

Or import `database/schema.sql` using **phpMyAdmin**.

---

## 3️⃣ Configure Database Connection

Edit:

```
config/database.php
```

Update credentials:

```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'elderly_care_db');
```

---

## 4️⃣ Configure Site URL

Edit:

```
config/config.php
```

```php
define('SITE_URL', 'http://localhost/elderly_care');
```

---

## 5️⃣ Set Folder Permissions

```
chmod 755 assets/images
```

---

## 6️⃣ Access the Application

Open browser:

```
http://localhost/elderly_care
```

or

```
http://localhost/elderly_care/index.php
```

---

# 🔑 Default Login Credentials

## 👨‍💼 Admin

| Field | Value |
|------|------|
| Username | admin |
| Password | admin123 |

---

## 👴 Elderly User

| Field | Value |
|------|------|
| Username | elderly1 |
| Password | elderly123 |

⚠️ Change these credentials in production.

---

# 📁 Project Structure

```
elderly_care/
│
├── config/
│   ├── config.php
│   └── database.php
│
├── css/
├── js/
├── php/
├── pages/
├── database/
├── assets/
│   └── images/
│
├── index.php
├── dashboard_elderly.php
├── dashboard_admin.php
└── README.md
```

---

# 🔒 Security Notes

- Use `password_hash()` for passwords
- Prevent **SQL Injection** using prepared statements
- Escape outputs with `htmlspecialchars()`
- Secure PHP sessions
- Validate file uploads

---

# 🚀 Future Enhancements

- 📄 PDF report generation
- 📧 Email notifications
- 📱 SMS emergency alerts
- 📲 Mobile application
- 💬 Real-time chat support
- 📅 Appointment scheduling
- ⏰ Medication reminders
- 👨‍👩‍👧 Family portal

---

# 📜 License

Academic project for educational purposes.

---

# 🙌 Credits

Developed using:

- HTML
- CSS
- JavaScript
- PHP
- MySQL

---

✨ Academic Full-Stack Web Development Project
