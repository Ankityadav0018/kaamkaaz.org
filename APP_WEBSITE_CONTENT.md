# Kaamkaaz (कामकाज) - Official Website Content (Comprehensive Master File)

This document contains every single detail, feature, system, and technical specification of the Kaamkaaz platform. This is the ultimate reference guide for building out your website, promotional material, or app documentation.

---

## 🌟 Hero Section (Home Page)
**Title:** Kaamkaaz (कामकाज)
**Subtitle:** India's Premium Hyperlocal Daily Wage Worker Platform
**Tagline:** Bridging the gap between reliable workers (Kaamgars) and local recruiters through verified identities and seamless matchmaking.

---

## 📖 About Us
Kaamkaaz is a high-fidelity, production-ready hyperlocal job marketplace designed specifically for daily wage (blue-collar) workers and local recruiters in rural and semi-urban India. Unlike traditional dispatch platforms, Kaamkaaz acts as an intermediary **job board and matchmaking system** that empowers the local community through verified identities and word-of-mouth growth.

---

## ✨ Key Highlights & Value Proposition
- **High-Trust, Low-Friction**: Every feature, from Aadhaar verification to the localized UI, is designed for the unique needs of the Indian workforce.
- **Multilingual Support**: Fully accessible in 13 Indian regional languages.
- **Premium User Experience**: Animated splash screens, interactive onboarding tours, and a zero-overflow UI design calibrated for all device sizes.
- **Smart Auth & Security**: Firebase-powered authentication, OTP verification, Biometric App Locks, and encrypted data storage.

---

## 🗣️ Supported Languages
Kaamkaaz is proudly built for Bharat. To ensure zero friction for our users, the app is fully translated and localized into **13 Indian Languages**:
1. English
2. Hindi (हिन्दी)
3. Punjabi (ਪੰਜਾਬੀ)
4. Bengali (বাংলা)
5. Telugu (తెలుగు)
6. Marathi (मराठी)
7. Tamil (தமிழ்)
8. Gujarati (ગુજરાતી)
9. Kannada (ಕನ್ನಡ)
10. Malayalam (മലയാളം)
11. Odia (ଓଡ଼ିଆ)
12. Urdu (اردو)
13. Rajasthani/Bhojpuri (राजस्थानी/भोजपुरी)

---

## 🚀 Deep Dive: Core Platform Systems

### 1. 🚨 Urgent Jobs Feature (On-Demand Hiring)
When time is of the essence, Kaamkaaz provides a specialized **Urgent Jobs** flow designed to get workers on-site immediately.
- **Priority Broadcast**: Recruiters can mark a job as "Urgent" during the posting process. This immediately bumps the job to the top of the feed for all nearby workers.
- **Instant Push Notifications**: Instead of waiting for workers to open the app, our system bypasses the standard feed and sends an instant, high-priority push notification directly to all verified workers in the immediate vicinity with the required skill set.
- **Rapid Matching**: Workers receive an unmissable alert. The first available and qualified worker to accept the job is instantly connected with the recruiter, reducing hiring time from hours down to mere minutes.
- **Premium Visibility UI**: Urgent jobs are highlighted with special badges and animations in the worker's job feed to guarantee maximum visibility.

### 2. 💼 Wallet & Payments Ecosystem
The Kaamkaaz platform includes a robust, secure built-in wallet system designed to handle recruiter top-ups and service charges transparently.
- **Instant Top-Ups**: Recruiters can instantly add funds to their Kaamkaaz wallet using UPI, NetBanking, or Credit/Debit Cards via our secure payment gateway integration.
- **Transaction History**: Transparent logging of all wallet deposits, job posting deductions, and refunds, accessible directly from the app.
- **Automated Deductions**: Seamless and automatic deduction of minor platform fees when a recruiter successfully posts a job or hires a worker.
- **Secure Webhooks**: Real-time server-to-server synchronization with payment gateways ensures that your wallet balance is updated instantly, even if the app loses internet connection during a transaction.

### 3. 💬 In-App Chat & Communication
- **Real-Time Messaging**: Built on Socket.io, users can chat instantly without leaving the app to discuss wages, share locations, or clarify job requirements.
- **Direct Calling & WhatsApp**: Recruiters can choose to connect with hired workers directly via a phone call or WhatsApp integration for easier offline communication.

### 4. 🏅 Skill Badges & Verification (KYC)
- **Multi-Step KYC**: Workers must submit a live selfie and Aadhaar details to get verified. This creates a high-trust environment.
- **Verified Skill Badges**: Once a worker completes their KYC and proves their expertise, admins grant them visual "Skill Badges" (e.g., Verified Plumber, Expert Electrician) that appear on their public profile, boosting their hiring rate.

### 5. 🤖 AI Job Assistant
- **Smart Drafting**: Recruiters who struggle to write job descriptions can use the built-in AI Assistant to automatically generate professional, detailed job postings based on a few keywords.

### 6. 🤝 Refer & Earn Program
- **Viral Growth**: A fully integrated referral system where users can share their unique referral code with friends via social media or WhatsApp.
- **Rewards**: Both the referrer and the referee receive automated wallet credits or rewards upon successful signup and first job completion.

### 7. 🛡️ Safety, Security & Offline Capabilities
- **App Lock**: Users can enable Biometric (Fingerprint/FaceID) or PIN-based app locks to secure their wallet and personal chats.
- **Emergency SOS**: A dedicated SOS button for workers to instantly alert emergency contacts and platform admins if they feel unsafe at a job site.
- **Smart Offline Mode**: The app intelligently caches job feeds and active chats so workers can still view accepted jobs and employer addresses even in areas with poor internet connectivity.

---

## 👥 Features by User Role

### 👷 For Workers (Kaamgars)
- **Discover Nearby Jobs**: Real-time job feed showing opportunities within a 15-30km radius using live GPS location.
- **One-Tap Apply**: Apply to jobs instantly and track application status (Pending/Accepted/Hired/Completed) in the "My Jobs" dashboard.
- **Media Portfolio ("Previous Work")**: Upload project descriptions, photos, and videos of previous work to showcase skills.
- **Ratings & Reputation**: Build a verifiable employment history based on recruiter feedback and star ratings.

### 🏢 For Recruiters
- **Post Jobs Instantly**: Create listings with precise GPS locations, specific skill requirements, wage details, and site photos.
- **Public Profile Search**: Effortlessly browse and filter public worker profiles across the platform without waiting for applications.
- **Manage Applicants**: Review worker profiles, check their Verified Skill Badges, past ratings, portfolios, and distance from the site.
- **Past Workers Network**: Access a history of previously hired workers to quickly re-invite trusted talent for future jobs.

### 🚚 For Drivers (Specialized Logistics Role)
- **Dedicated Logistics Portal**: Specific onboarding, tracking, and job management for local transport drivers and vehicle owners.
- **Vehicle Registration (KYC)**: Secure document tracking for driving licenses, RC, and vehicle details.

### 🛡️ For Admins (Platform Management)
- **Analytics Dashboard**: Real-time visualization of platform health, registration trends, and job distribution.
- **KYC & Verification Queue**: Manage and verify worker/driver documents and recruiter onboarding requests securely.
- **Dispute & Reporting System**: Robust tools for investigating reported jobs or misbehaving users, alongside dispute resolutions.

---

## ⚖️ Legal & Policies

### 1. Terms & Conditions
- **User Verification**: All users must submit valid government-issued ID (such as Aadhaar) to be granted "Verified" status.
- **Platform Role**: Kaamkaaz acts strictly as an intermediary and matchmaking platform. We do not directly employ workers or guarantee job placement.
- **Code of Conduct**: Any misuse of the platform, including posting fraudulent jobs, harassment, or failing to pay agreed-upon wages, will result in immediate account suspension.

### 2. Privacy Policy
- **Data Collection**: We collect essential information such as GPS location (to match hyperlocal jobs), phone numbers, and identity documents (for KYC purposes).
- **Data Security**: All sensitive data, including biometrics and passwords, are encrypted. We do not sell personal data to third parties.
- **Camera & Storage Access**: Camera and storage permissions are strictly used for uploading profile pictures, KYC documents, and work portfolios.

### 3. Payment & Refund Policy
- **Recruiter Wallet Top-Ups**: Wallet top-ups are generally non-refundable and must be utilized within the platform for posting jobs or accessing premium services.
- **Failed Transactions**: If a top-up transaction fails but money is deducted from the user's bank account, it will automatically be refunded by the payment gateway within 5-7 business days.
- **Disputes**: In the event of a severe dispute regarding platform services, users may raise a ticket via the "Report Problem" screen for admin review. Refunds in such cases are at the sole discretion of Kaamkaaz administration.

---

## 🛠️ Technical Foundation (For Tech/Developer Page)
- **Frontend Application**: Built on Flutter (Dart) with Riverpod state management and GoRouter, fully optimized for Android SDK 36.
- **Backend API Ecosystem**: Scalable Node.js and Express.js architecture.
- **Database Infrastructure**: MongoDB with Geospatial indexing (`2dsphere`) for lightning-fast location-based matching.
- **Real-Time Connectivity**: Socket.io for live in-app chat, paired with Firebase for Auth, Crashlytics, and Push Notifications.
- **Media Storage**: Cloudinary integration for fast, secure KYC document and portfolio photo storage.

---
*End of Document. This file now contains the absolute complete breakdown of the Kaamkaaz platform.*
