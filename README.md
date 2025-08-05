# ✅ Todo Task Manager App

Welcome to the **Todo Task Manager App** – a lightweight, real-time, and user-friendly mobile solution for managing your daily tasks. Built with **React Native (Expo)** and **Firebase**, it keeps your productivity in sync across devices.

---

## ✨ Overview

This mobile application enables users to:
- Authenticate securely via **Google**
- Create, view, edit, and delete tasks
- Organize tasks by **status**, **due dates**, and **priority**
- Enjoy a modern, smooth, and responsive interface with intuitive navigation

---

## 🔧 Built With

- **Frontend**: React Native (Expo SDK)
- **Backend**: Firebase Firestore (Realtime Database)
- **Authentication**: Firebase Auth (Google Sign-In)

---

## 🔐 User Authentication

- One-tap Google login via Firebase Auth
- Error handling included for smoother experience

---

## 📋 Task Operations

Each task includes the following details:
- **Title**
- **Description**
- **Due Date**
- **Priority Level**
- **Status** (Open or Completed)

You can:
- Create new tasks instantly
- Update or mark tasks as complete
- Swipe to delete tasks
- Pull down to refresh

---

## 📱 UI/UX Highlights

- Tab navigation for easy filtering (All / Completed / Pending)
- Floating Action Button (FAB) for quick task additions
- Subtle animations and empty-state illustrations
- Search & filter built-in for easy access to tasks

---

## 📂 Project Layout

```
/src
│
├── components/     → Reusable widgets like TaskCard, FAB
├── screens/        → LoginScreen, HomeScreen, AddTaskScreen
├── navigation/     → Navigation stack and tab configs
├── services/       → Firebase auth and database logic
└── utils/          → Constants and helpers

App.js              → Main entry point
firebaseConfig.js   → Firebase config file
```

---

## 🚀 Getting Started

1. **Clone this repository**

```bash
git clone https://github.com/Mathumitha-Ashokkumar16/To_Do_App.git
```

2. **Install dependencies**

```bash
npm install
```

3. **Configure Firebase**

Create `firebaseConfig.js` and paste your Firebase project config:

```js
export const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
};
```

4. **Run the app**

```bash
npx expo start
```

---

## 🧠 Design Approach

- Modular structure and clean separation of logic
- Firebase abstraction for better scalability
- Offline support using Firestore’s local caching
- Reusable components and hooks for maintainability

---

## 🌱 Future Enhancements

- Add user account switch & multi-user support
- Task color tags for priority levels
- Reminder notifications (via local notifications)
- Dark mode toggle
- CSV export feature

---

## 🎬 Demo Preview

🎥 Watch the live walkthrough here: https://drive.google.com/file/d/1yfRIXrVAbHf6ihWiq56cGb_WmN109KCW/view?usp=drivesdk

---

## 📝 Note

This project is submitted as part of a hackathon hosted by [Katomaran Technologies](https://www.katomaran.com).

---

Thank you for checking out the Todo Task Manager App!