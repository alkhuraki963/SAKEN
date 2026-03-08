# 🏠 SAKEN - Backend API
### Apartment Rental Platform


## 📋 Overview

**SAKEN** is a third-year university project for the "Programming Languages" course. It aims to develop a complete apartment booking application that allows users (tenants and hosts) to rent apartments, with an admin dashboard for system management.

> 💡 **Note:** This repository contains only the **Backend code** built with Laravel 11. The project was implemented as a university requirement, with a strong focus on teamwork and collaboration among team members.

---
## ✨ Key Features

### 👤 User Management
- Register with mobile number (as host or tenant)
- Admin approval required before account activation
- Complete user profile including:
  - First name & last name
  - Profile picture
  - Date of birth
- Login / Logout using Laravel Sanctum

### 🏘️ Apartment Management
- Add and view apartments with detailed specifications
- Browse all available apartments
- Booking approval system (host must confirm requests)
- Prevent overlapping bookings for the same apartment

### 🔍 Advanced Search & Filtering
- Filter apartments by:
  - Governorate
  - City
  - Price range
  - Specific amenities

### 📅 Booking System
- Book apartments for specific periods
- Cancel bookings
- Modify bookings (requires host approval)
- View all bookings (past, current, cancelled)

### ⭐ Ratings & Reviews
- Rate apartments after stay
- Display ratings to other users

### 🔔 Notification System
- Real-time notifications for booking status changes
- Updates for users

### ❤️ Favorites
- Add apartments to a favorites list
- Book directly from favorites

### 👑 Admin Panel
- Flutter dashboard for system administrators
- Approve or reject registration requests
- Remove users if necessary

---

## 🛠️ Technologies Used

- **Laravel 11** - PHP framework
- **MySQL 8.0** - Database
- **Laravel Sanctum** - Authentication
- **PHP 8.2** - Programming language

---

## 📦 Requirements

- PHP >= 8.2
- Composer
- MySQL >= 8.0
- Node.js & NPM (for Laravel Mix)

---

## 👥 Backend Team

| Name | Role | GitHub |
|------|------|--------|
| [ِAbdulrahmn Al-Khuraki] | Backend Developer | [@alkhuraki963](https://github.com/alkhuraki963) |
| [Mahmoud Saad] | Backend Developer | [@MahmoudSaad000](https://github.com/MahmoudSaad000) |
| [Omar Yassin] | Backend Developer | [@omaryassin1187-beep](https://github.com/omaryassin1187-beep) |

---

## 🤝 Collaboration & Teamwork

This project was developed by a team of five members, with tasks divided between backend and frontend. Key collaboration aspects included:

- Using **Git** and **GitHub** for version control and collaboration
- Code reviews and mutual assistance
- Regular meetings to track progress and resolve issues

---

## 💭 Learning Experience

This project was a great opportunity to apply the programming concepts. We built a complete application from scratch using Laravel and Flutter, tackling real-world challenges such as:

- Designing a relational database to meet system requirements
- Building secure RESTful APIs
- Implementing authentication and authorization
- Handling complex business logic (preventing booking conflicts, approval workflows)

---

## 📄 License

This project is for educational purposes only – a third-year university project.

---

**Note:** This repository contains only the backend code.
