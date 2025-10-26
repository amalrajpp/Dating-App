# 💞 Flutter Location-Based Dating App

A modern, high-performance **Flutter** application that connects people based on **location and shared interests**.  
Built with **Firebase** for backend services and **GetX** for reactive state management, the app delivers a seamless swiping, matching, and chatting experience — optimized for scalability and real-time performance.

---

## 🚀 Overview

This app enables users to:
- Discover nearby profiles based on **geolocation**
- Swipe to **like or skip** other users
- Match with mutual likes
- **Chat** in real-time after matching
- Manage their **profiles**, preferences, and distance filters

It is designed following **Clean Architecture** for maintainability, **GetX** for minimal boilerplate, and **Firestore** for real-time matching.

---

## ✨ Features

### 👤 User Profiles
- Register and log in using **Firebase Authentication**
- Complete profile with photos, bio, age, interests, and location
- Update profile details anytime

### 📍 Location-Based Matching
- Uses **GeoFlutterFire Plus** for efficient geolocation querying
- Find and display nearby users within a customizable distance
- Prevents repeated profile suggestions

### ❤️ Swipe & Match System
- Swipe right to like and left to skip
- Instant mutual match notification
- Real-time updates through **Firestore streams**

### 💬 Real-Time Chat
- Secure, fast, and smooth chatting experience
- Messages stored efficiently in **subcollections** for scalability
- Typing indicators and timestamps supported

### ⚙️ Other Features
- **Dark mode** and modern UI design
- **GetX** for reactive UI, state management, and navigation
- **Firestore security rules** for safe access
- Optimized **reads/writes** to minimize Firebase costs

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| Framework | Flutter (Dart) |
| State Management | GetX |
| Backend | Firebase Firestore |
| Authentication | Firebase Auth |
| Location | GeoFlutterFire Plus |
| Storage | Firebase Storage |
| Architecture | Clean Architecture (Presentation, Domain, Data layers) |

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/flutter-dating-app.git
cd flutter-dating-app
