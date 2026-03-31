# 📘 QudwahFlix — Project Documentation

## 📌 Overview
QudwahFlix is a full-featured mobile application built using Flutter, focused on delivering Islamic learning content, e-commerce, and subscription-based services in a single platform.

The system integrates authentication, video streaming, payments, and gamified learning to create an engaging and scalable user experience.

---

## 🚀 Key Features

### 🔐 Authentication System
- Email & password login
- Google & Apple Sign-In
- User profile management
- Role-based access (admin detection)
- Persistent login session

---

### 📱 Core App Experience
- Personalized home dashboard
- Daily content (expressions, learning materials)
- Video streaming (subscription-based access)
- Product catalog with cart system
- Class registration & onboarding flow

---

### 💳 Payment & Subscription System
- Integrated payment gateway (SenangPay)
- One-time & installment payments
- Real-time payment status tracking
- Subscription activation & expiry tracking
- Automated backend workflow after payment

---

### 🛒 Order Management
- Cart & checkout system
- Order creation & tracking
- Shipping address integration (Google Places API)
- Real-time order updates

---

### 🎮 Gamified Learning
- Multiple mini-games:
  - Word guessing
  - Image selection
  - Matching games
  - Word search & scramble
- Score tracking & progression system
- Firebase-powered real-time data

---

### 📚 Learning Features
- Video lessons with access control
- Doa, Hadith, Zikir, and Solat modules
- Arabic-Malay dictionary (Kamus)
- Interactive chatbot support

---

## 🏗 System Architecture

### Frontend
- Flutter (Dart)
- Responsive UI with Material Design
- State-driven UI updates

### Backend (Firebase)
- Firebase Authentication
- Cloud Firestore (real-time database)
- Firebase Storage (media handling)
- Cloud Messaging (notifications)

### External Integrations
- SenangPay (payment gateway)
- Google Places API (address autocomplete)

---

## 🔄 Key Workflows

### Payment Flow
1. User selects product or class
2. Payment request created
3. Redirect to SenangPay
4. Payment verification
5. Firestore updated (transaction + status)
6. Trigger:
   - Subscription activation OR
   - Order fulfillment

---

### Authentication Flow
1. User logs in / registers
2. Profile stored in Firestore
3. Auth state listener controls navigation
4. Access granted based on user state

---

## 📂 Project Structure (Simplified)


---

## 🧠 My Contributions

- Developed full mobile application using Flutter
- Implemented complete authentication system
- Built payment & subscription logic with real-world flow
- Designed Firestore database structure
- Integrated external APIs (payment & location)
- Developed interactive learning games
- Managed app navigation and state flow
- Handled real-time updates and error handling

---

## ⚡ Highlights

- Real-world payment integration (not mock)
- Complex multi-feature system in one app
- Clean separation of services & UI
- Scalable Firebase architecture
- Production-ready structure

---

## 📌 Notes
This project was developed during my internship and is confidential.  
Source code is not publicly available.  
This repository highlights the features, structure, and implementation of the system.

---

## 🧑‍💻 Project Context
- Developed during internship at CMN Alqudwah Learning
- Collaborated in a small team environment
