# 🍔 FoodieGo

**A modern food delivery app built with Flutter & Firebase — designed with production-level UI polish, inspired by industry leaders like Swiggy and Zomato.**

FoodieGo is a fully functional, end-to-end food ordering experience — from browsing restaurants to secure checkout — built and tested on a real Android device.

---

## ✨ Features

### 🔐 Authentication
- Email & Phone OTP authentication via Firebase
- Animated splash screen (fade + scale + pulsing dots loader)
- Consistent two-zone login, register & OTP screens (orange header + white card)
- Poppins typography throughout

### 🏠 Home Experience
- Deliver-to address bar with live location picker
- Notification bell & cart icons with live badge counters
- Auto-scrolling promotional banner carousel
- Browse by category with horizontal scroll & outlined selection chips
- Popular foods section with favorites & quick add-to-cart

### 🍽️ Ordering & Payments
- Detailed food screens with ratings, delivery time & INR pricing
- Cart with quantity controls & order summary
- Razorpay payment integration — Credit Card, UPI & Cash on Delivery
- Failed payment tracking synced to Firestore
- Order history with status badges (including failed payments)

### 👤 Profile & More
- Curved-header profile screen with avatar overlap design
- Editable profile, fully synced with Firestore
- Search with live results & category filters
- Favorites synced across sessions
- Restaurant listings across 3 branches (Andheri, Bandra, Powai) with maps & call-now
- Notifications screen
- Shimmer loading states & empty-state retry UI throughout

---

## 🎨 Design Highlights

- Custom design system — consistent colors, typography & spacing
- Primary color `#FF6B35` · Background `#F0F1F5`
- Curved header clipper on Profile screens
- Smooth animations: splash sequence, card slide-ups, brand fade-ins
- Custom app icon — bold Poppins "FoodieGo" mark on orange rounded square

---

## 📱 Screenshots

<!-- Add screenshots here -->
<!-- Example:
| Splash | Login | Home |
|--------|-------|------|
| ![Splash](screenshots/splash.png) | ![Login](screenshots/login.png) | ![Home](screenshots/home.png) |
-->

---

## 🛠️ Tech Stack

**Framework:** Flutter (Dart)
**Backend:** Firebase Auth, Cloud Firestore
**State Management:** Provider
**Payments:** Razorpay
**Location:** Google Maps / Flutter Map, Geolocator, Geocoding

**Key Packages:**
`provider` · `google_fonts` · `cached_network_image` · `carousel_slider` · `flutter_svg` · `shimmer` · `intl` · `firebase_core` · `firebase_auth` · `cloud_firestore` · `flutter_map` · `geolocator` · `geocoding` · `latlong2` · `razorpay_flutter` · `url_launcher`

---

## 📥 Download & Install

Want to try FoodieGo on your Android device?

1. Go to the [**Releases**](../../releases) section of this repo
2. Download the latest `app-release.apk`
3. On your Android device, enable **"Install from unknown sources"** (Settings → Security)
4. Open the downloaded APK and install
5. Launch FoodieGo and explore!

> 📌 **Note:** This app is for demonstration and testing purposes.

---

## 🔒 Source Code

This repository is a **showcase page** for the FoodieGo project. The full source code is maintained in a private repository to protect the project's implementation. This repo contains project details, screenshots, and a downloadable APK for testing purposes.

---

## 💼 Hire Me

I'm a Flutter developer specializing in cross-platform mobile apps with Firebase backends. If you liked what you saw, let's talk about your project.

**Contra:** [Your Contra Profile Link]

---

<p align="center">Built with ❤️ using Flutter, by Soham Shinde</p>
