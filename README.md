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
- ❤️ Update daily health information (Sugar level, Blood Pressure, Overall Condition)
- 🍽️ Select meals for breakfast, lunch, snacks, and dinner
- 📊 View health history
- 🍱 View meal history
- 🚨 Emergency alert button (24/7 support)
- 💰 View account balance

---

## 🖥️ Admin / Management Dashboard
- 📋 View today's health updates
- 🍽️ Monitor meal selections
- 🏠 Manage resident list with room numbers
- 🚨 Handle emergency alerts
- 💳 View financial summaries
- 📈 Generate monthly reports
- 📊 View resident statistics & analytics

---

# 👥 Resident Management
- 👤 Resident information (Name, Age, Photo, Room Number)
- 🏥 Medical conditions (Diabetes, Blood Pressure, Allergies)
- 📅 Daily health logs
- 💊 Medicine schedule tracking

---

# 🍽️ Food & Kitchen Management
- 🩺 Diabetes-friendly
- 🧂 Low-salt
- 🥣 Soft food
- ❤️ Heart patient diet
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

---

# ⭐ Rating & Feedback
- 🍽️ Food service rating
- 🧹 Cleanliness rating
- 🏥 Medical care rating
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
- PHP 7.4+
- MySQL 5.7+
- Apache / Nginx
- PHP extensions: `mysqli`, `pdo_mysql`, `mbstring`

---

## 📥 Setup Steps
1. Download or clone project
2. Import database schema (`database/schema.sql`)
3. Configure database connection (`config/database.php`)
4. Configure site URL (`config/config.php`)
5. Set folder permissions (`assets/images`)
6. Access the application via browser

---

# 🔑 Default Login Credentials

## 👨‍💼 Admin
| Field | Value |
|------|------|
| Username | admin |
| Password | admin123 |

## 👴 Elderly User
| Field | Value |
|------|------|
| Username | elderly1 |
| Password | elderly123 |

⚠️ Change credentials in production.

---

# 📁 Project Structure

```
elderly_care/
├── config/
│   ├── config.php          # General configuration
│   └── database.php        # Database configuration
├── css/
│   ├── style.css           # Main stylesheet
│   └── admin.css           # Admin-specific styles
├── js/
│   ├── main.js             # Common JavaScript
│   ├── dashboard_elderly.js  # Elderly dashboard JS
│   └── dashboard_admin.js    # Admin dashboard JS
├── php/
│   ├── login.php           # Login processing
│   ├── logout.php          # Logout processing
│   ├── update_health.php   # Health update handler
│   ├── submit_meals.php    # Meal selection handler
│   ├── emergency.php       # Emergency alert handler
│   ├── get_health_history.php  # Health history API
│   ├── get_meal_history.php    # Meal history API
│   ├── get_meal_plans.php      # Meal plans API
│   └── admin/
│       ├── respond_emergency.php  # Emergency response handler
│       └── generate_report.php    # Report generator
├── pages/
│   ├── home.php            # Home page
│   ├── login.php           # Login page
│   ├── about.php           # About page
│   ├── services.php        # Services page
│   ├── contact.php         # Contact page
│   └── admin/
│       ├── overview.php    # Admin overview
│       ├── residents.php   # Residents list
│       ├── health.php      # Health updates
│       ├── meals.php       # Meal selections
│       ├── emergencies.php # Emergency alerts
│       ├── finance.php     # Financial management
│       └── reports.php     # Reports & analytics
├── database/
│   └── schema.sql          # Database schema
├── assets/
│   └── images/             # Resident photos
├── index.php               # Main entry point
├── dashboard_elderly.php   # Elderly user dashboard
├── dashboard_admin.php     # Admin dashboard
└── README.md               # Project README
```

---

# 🔒 Security Notes
- Use `password_hash()` for passwords
- Prevent SQL Injection using prepared statements
- Escape output with `htmlspecialchars()`
- Secure PHP sessions
- Validate file uploads

---

# 🚀 Future Enhancements
- PDF report generation
- Email notifications
- SMS emergency alerts
- Mobile app
- Real-time chat support
- Appointment scheduling
- Medication reminders
- Family member portal

---

# 📜 License
Academic project for educational purposes.

---

# 🙌 Credits
- HTML
- CSS
- JavaScript
- PHP
- MySQL

---

✨ Academic Full-Stack Web Development Project
