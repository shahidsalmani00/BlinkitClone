# 🛒 Blinkit Clone App – Ultra-Fast Grocery Delivery (10-Minute Delivery)

This repository contains two fully functional Android apps:

- 📱 **User App** – For customers to browse products, place orders, and track deliveries.
- 🧑‍💼 **Admin App** – For store managers/admins to manage products, track orders, and control delivery flow.

This Blinkit clone is inspired by real-time delivery services like **Blinkit** and **Zepto**, built entirely with **Kotlin, XML, and Firebase**.

---

## 📦 Project Modules

BlinkitClone/
├── UserApp/ # Android App for Customers
├── AdminApp/ # Android App for Store/Admin Panel
├── assets/ # Screenshots for README
└── README.md


---

## 👤 User App – Features

> Location: `/UserApp/`

- 📍 Auto location detection using Google Maps API.
- 🛒 Browse categories like Grocery, Dairy, Snacks, etc.
- 🛍️ Add to Cart & Place orders in one tap.
- 🔐 Login/Signup with Firebase Authentication.
- 🧾 View order history & live order status.
- 🚚 Track delivery agent in real time (live order tracking).

---

## 🧑‍💼 Admin App – Features

> Location: `/AdminApp/`

- 📦 Add/Edit/Delete product categories & items.
- 📊 View all placed orders from customers.
- 🚚 Update order status: Pending → Out for delivery → Delivered.
- 🔔 Send order-related notifications (coming soon).
- 📁 Upload product images using Firebase Storage.
- 👥 View user data and order trends.

---

## 🛠 Tech Stack

| Module      | Technology             |
|-------------|------------------------|
| UI Design   | XML                    |
| Language    | Kotlin (Android)       |
| Backend     | Firebase Realtime DB   |
| Auth        | Firebase Authentication|
| Storage     | Firebase Storage       |
| Location    | Google Maps API        |

---

## 📸 Screenshots

> Upload your screenshots in the `assets/screenshots/` folder and link them here.

### 📱 User App

 !(<img width="158" alt="image" src="https://github.com/user-attachments/assets/78f279e0-ad2b-4e9d-81e0-98e191753e3b" />
 !(<img width="163" alt="image" src="https://github.com/user-attachments/assets/87eaeb18-0a9d-485b-9e3d-163b2c56bfdf" />
 !(<img width="163" alt="image" src="https://github.com/user-attachments/assets/e9933400-6a9c-4bff-9e5a-778733c35258" />
 !<img width="164" alt="image" src="https://github.com/user-attachments/assets/560378f0-96f9-4cd2-9c9d-ddff313c9ac2" />

---

## 🔧 Getting Started

### 📲 User App Setup

1. Open `/UserApp/` in Android Studio.
2. Add your `google-services.json` file to the `app/` directory.
3. Connect Firebase Auth, Realtime Database, and Storage.
4. Run the app on emulator or device.

### 🧑‍💼 Admin App Setup

1. Open `/AdminApp/` in Android Studio.
2. Add the same Firebase project `google-services.json`.
3. Sync Firebase Database rules and connect Auth + Storage.
4. Run the admin app on emulator or device.

---

## 🔐 Firebase Configuration

Enable the following services from [Firebase Console](https://console.firebase.google.com/):

- ✅ **Authentication** (Email/Password)
- ✅ **Realtime Database**
- ✅ **Firebase Storage**

---

## 🚀 Future Plans

- ✅ Live order tracking via delivery agent app
- ⏳ Integrated payment gateway (UPI/Razorpay)
- ✅ Search & Filter functionality
- 🔔 Push notifications using Firebase Cloud Messaging
- 📈 Admin analytics dashboard


