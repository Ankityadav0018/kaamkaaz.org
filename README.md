# Kaamkaaz (कामकाज)
### Hyperlocal Daily Wage Worker Platform

![Flutter](https://img.shields.io/badge/Frontend-Flutter_3.x-02569B?logo=flutter)
![Node.js](https://img.shields.io/badge/Backend-Node.js_Express-339933?logo=nodedotjs)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb)
![Supabase](https://img.shields.io/badge/Auth-Supabase-3ECF8E?logo=supabase)
![Firebase](https://img.shields.io/badge/Notifications-Firebase-FFCA28?logo=firebase)
![Build](https://img.shields.io/badge/Release-AAB_Generated-success)
[![Play Store](https://img.shields.io/badge/Play_Store-Coming_Soon-lightgrey?logo=google-play)]()

> Connecting blue-collar workers with local recruiters across rural and semi-urban India.

---

## 📌 About the Project

**Kaamkaaz** is a production-ready hyperlocal job marketplace built for daily wage workers
and local recruiters in India. It bridges the gap between workers (Kaamgars) and recruiters
through verified identities, GPS-based job matching, and a seamless hiring experience —
designed with a "High-Trust, Low-Friction" philosophy.

> 🔒 This repository is private. Code available on request.

---

## ✨ Key Features

### 👷 For Workers
- GPS-based job discovery within 15–30km radius
- One-tap job application with status tracking
- KYC verification (Aadhaar + Live Selfie + Driving License)
- Skill badges, media portfolio, and work history
- Emergency SOS alerts and offline mode

### 🏢 For Recruiters
- Post jobs with GPS location, skill requirements, and site photos
- Review verified worker profiles, ratings, and portfolios
- Connect via Direct Call, WhatsApp, or In-App Chat
- Re-invite trusted workers from past hiring history

### ⚙️ For Admins
- Real-time analytics dashboard
- KYC verification queue management
- Dispute resolution system
- Withdrawal management

### 💎 App Highlights
- 13 Indian language support (Hindi, Punjabi, Tamil, Telugu, and more)
- Biometric login + OTP authentication
- Real-time chat powered by Socket.io
- Offline mode with intelligent local caching
- Zero-overflow UI across all device sizes

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Mobile Frontend | Flutter (Dart), Riverpod, GoRouter |
| Backend | Node.js, Express.js |
| Database | MongoDB with 2dsphere Geospatial Indexing |
| Authentication | Supabase Auth + Firebase Auth |
| Real-Time | Socket.io |
| Push Notifications | Firebase Admin SDK |
| Media Storage | Cloudinary |
| Error Tracking | Firebase Crashlytics |
| Local Security | flutter_secure_storage |

---

## 📱 Screenshots
<img width="1440" height="2560" alt="kaamkaaz_screenshot_1" src="https://github.com/user-attachments/assets/6efa122e-a18b-4f4f-82fc-02ff3a9f586c" />

> Coming Soon

---

## 🏗️ Architecture

kaamkaaz/
├── app/                  # Flutter Mobile Application
│   ├── lib/
│   │   ├── l10n/         # 13 Language Translations
│   │   ├── models/       # Data Models
│   │   ├── providers/    # Riverpod State Management
│   │   ├── screens/      # Worker, Recruiter, Admin UI
│   │   ├── services/     # API & Socket Services
│   │   └── widgets/      # Reusable Components
│   └── assets/           # Icons, Images, Translations
└── backend/              # Node.js Express API
├── controllers/      # Business Logic
├── models/           # Mongoose Schemas
├── routes/           # API Endpoints
└── server.js         # Entry Point
---

## 🚀 Getting Started

### Backend
```bash
cd backend
npm install
# Add your .env file (see below)
npm start
# Server runs on port 5005
```

### Frontend
```bash
cd app
flutter pub get
flutter run
# For release build:
flutter build appbundle --release
```

### Environment Variables
| Variable | Description |
|---|---|
| `MONGODB_URI` | MongoDB connection string |
| `JWT_SECRET` | JWT signing secret |
| `FIREBASE_SERVICE_ACCOUNT` | Firebase service account JSON |
| `CLOUDINARY_URL` | Cloudinary media storage URL |
| `SUPABASE_URL` | Supabase project URL |
| `SUPABASE_ANON_KEY` | Supabase anonymous key |
| `PORT` | Server port (default 5005) |

---

## 👨‍💻 Developer

**Ankit Yadav**
- Built with Flutter + Node.js + MongoDB
- Deployed on Google Play Store (Coming Soon)

---

## 📄 License

This project is privately maintained.
© 2026 Kaamkaaz. All rights reserved.
