# Transitely – Smart Ride Sharing Platform

Transitely is a modern smart ride-sharing platform inspired by Uber, developed as a CSE327 Software Design Project. The system provides separate modules for Riders, Drivers, and Admins with both mobile and web-based applications.

The project combines Flutter mobile development, Node.js backend services, and a React-based admin portal to create a complete transportation management ecosystem.

---

# Features

## Rider Features

* Rider registration and login
* OTP verification
* Book rides in real time
* View nearby drivers
* Promo code discount system
* Ride history tracking
* Driver history visibility before booking
* Rebook same driver functionality
* 5% cashback for rebooking same driver
* Ride fare estimation
* In-app notifications
* Payment management
* Rating and review system

---

## Driver Features

* Driver registration and authentication
* Driver profile management
* Upload driving documents
* Online/offline availability control
* Accept/reject ride requests
* Ride completion tracking
* Earnings overview
* Ride history management
* Driver verification system

---

## Admin Features

* Admin dashboard
* Manage riders and drivers
* Verify driver documents
* Monitor ride requests
* Complaint management
* Promo code management
* Payment monitoring
* Notification management
* User activity monitoring

---

# Unique Features

## 1. Promo Code Coupon System

Transitely allows riders to apply promotional discount codes during ride booking.

---

## 2. Driver History Visibility

The platform allows riders to view a driver's previous history and information before confirming a ride, improving transparency and safety.

---

## 3. Rebook Same Driver with Cashback

Riders can rebook their preferred drivers and receive a 5% cashback reward.

---

# Project Architecture

```text
Transitely
│
├── backend        → Node.js + Express Backend API
├── frontend       → React/Vite Admin Web Portal
├── frontend_app   → Flutter Rider & Driver Mobile App
```

---

# Technologies Used

| Component             | Technology           |
| --------------------- | -------------------- |
| Mobile App            | Flutter              |
| Frontend Admin Portal | React.js + Vite      |
| Backend               | Node.js + Express.js |
| Database              | MongoDB / MySQL      |
| Authentication        | JWT + OTP            |
| API Communication     | REST API             |
| Mobile Language       | Dart                 |
| Styling               | Tailwind CSS         |
| Version Control       | Git + GitHub         |

---

# Folder Structure

## backend/

Contains:

* Express server
* API routes
* Controllers
* Database models
* Middleware
* Authentication logic
* Ride booking logic
* Payment processing
* Driver assignment logic

Main backend entry point:

```text
backend/src/app.js
```

---

## frontend/

Contains the Admin Web Portal.

Built using:

* React.js
* Vite
* Tailwind CSS

Runs on browser.

---

## frontend_app/

Contains Flutter mobile application.

Used for:

* Rider app
* Driver app

Main Flutter entry point:

```text
frontend_app/lib/main.dart
```

---

# Installation Guide

## 1. Clone Repository

```bash
git clone https://github.com/diyanazia/Transitely.git
```

---

# Backend Setup

```bash
cd backend
npm install
npm run dev
```

Backend runs on:

```text
http://localhost:5000
```

---

# Frontend Admin Portal Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

# Flutter Mobile App Setup

```bash
cd frontend_app
flutter pub get
flutter run
```

---

# Android Device Setup

1. Enable Developer Options
2. Enable USB Debugging
3. Connect phone with USB
4. Run:

```bash
flutter devices
```

5. Run app:

```bash
flutter run -d <device-id>
```

---

# Backend API Connection for Physical Device

When running on a real Android phone, replace:

```dart
http://localhost:5000
```

with:

```dart
http://YOUR_PC_IP:5000
```

Example:

```dart
http://192.168.0.122:5000
```

---

# Important Commands

## Backend

```bash
npm run dev
```

---

## Admin Portal

```bash
npm run dev
```

---

## Flutter App

```bash
flutter run
```

---

# White Box Testing

White-box testing was conducted on:

* Authentication module
* OTP verification
* Ride booking logic
* Fare calculation
* Driver assignment
* Payment processing
* Admin operations
* Middleware authorization

Testing techniques used:

* Branch Coverage
* Condition Coverage
* Basis Path Testing
* Cyclomatic Complexity Analysis


---

# Team Members
1. Nazia Faruque Diya 
2. Sadia Abedin Medha
3. Suraiya Bintee Rashid

---


