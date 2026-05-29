# 🌿 G.One — AI-Driven Waste Management System

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

**A full-stack, AI-powered waste management platform built with Flutter and Spring Boot**

</div>

---

## 📱 About G.One

G.One is a cross-platform waste management application that empowers citizens to report illegal dumping, schedule waste pickups, find nearest collection centers, and earn rewards — while giving administrators complete control over operations through a dedicated dashboard.

The system uses **Roboflow AI** to automatically classify waste types through the phone camera, making reporting faster and more accurate.

---

🚀 Live Demo

Citizen App (Flutter)

🔗 https://appetize.io/app/b_tmudra5u7uhtscvsgzt7y3mesq

Admin Dashboard

🔗 https://gone-admin.vercel.app

Backend API (Spring Boot REST API)

BaseUrl : 🔗 https://gonebackend-production.up.railway.app

---

## 🏗️ Repository Structure

This project is organized as a **polyrepo** — each component lives in its own repository:

| Repository | Description | Tech |
|---|---|---|
| [gone-backend](../gone-backend) | Spring Boot REST API — authentication, reports, pickups, gamification | Java 17, Spring Boot, JWT, H2 |
| [gone-citizen](../gone-citizen) | Citizen mobile app — report, scan, leaderboard, schedule pickup | Flutter, Dart, BLoC |
| [gone-admin](../gone-admin) | Admin dashboard — manage reports, users, pickups, training | Flutter, Dart, Provider |

---

## ✨ Key Features

- 🤖 **AI Waste Scanner** — Roboflow-powered real-time waste classification via phone camera
- 📍 **GPS Report Submission** — Citizens report illegal dumping with photo and auto-tagged location
- 🏆 **Gamification** — Points, levels, streaks, badges and live leaderboard
- 📦 **Pickup Scheduling** — End-to-end pickup booking with admin assignment and status tracking
- 🗺️ **Nearest Centers** — Haversine formula calculates distance to nearest waste collection centers
- 🎓 **Training Videos** — Admin-uploaded modules with XP rewards on completion
- 🔐 **JWT Security** — BCrypt password hashing, token-based authentication

---

## 🛠️ Tech Stack

**Backend**
- Java 17, Spring Boot 3.2.3
- Spring Security + JWT (jjwt 0.11.5)
- JPA / Hibernate 6.4 + H2 Database
- BCrypt, Lombok, REST API (13+ endpoints)

**Citizen Mobile App**
- Flutter 3.x / Dart
- BLoC state management
- Clean Architecture
- HTTP, Image Picker, Google Maps, Geolocator

**Admin Dashboard (Web)**
- Flutter Web 3.x / Dart
- Provider state management
- Responsive web UI
- REST API integration with JWT

**AI**
- Roboflow API — real-time waste classification model
---

## 🚀 Getting Started

Clone all three repositories:

```bash
git clone https://github.com/GOne-App/gone-backend
git clone https://github.com/GOne-App/gone-citizen
git clone https://github.com/GOne-App/gone-admin
```

Start the backend first, then run either Flutter app. See individual repo READMEs for setup instructions.

---

## 👨‍💻 Developer

**Shubham Srivastava**
