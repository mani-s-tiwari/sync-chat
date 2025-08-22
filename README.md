# 💬 Sync Chat - Real-time Chat Application

Sync Chat is a lightweight, real-time chat application that allows users to create chat rooms and communicate instantly by sharing a simple room key.  
It’s built with Firebase and works seamlessly across devices.

---

## 🚀 Features
- 🔐 **Anonymous Authentication** – No registration required  
- 🌐 **Real-time Messaging** – Powered by Firebase Firestore  
- 📱 **Mobile Responsive** – Works on all devices  
- 🎨 **Theme Support** – Light and dark modes  
- 🔔 **Push Notifications** – Get notified of new messages  
- 📋 **Room Management** – Create, join, and leave chat rooms  
- ✂️ **Easy Sharing** – Copy or share room keys directly  

---

## 📖 How It Works
1. Enter your **name** (stored locally only).  
2. Create a **new room** or join an **existing room** with a room key.  
3. Share the room key with others.  
4. Start messaging instantly in real-time.  

---

## 🛠️ Technology Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Firebase (Authentication, Firestore, Cloud Messaging)  
- **Icons:** [Font Awesome](https://fontawesome.com/)  
- **Hosting:** Any static hosting service (e.g., Firebase Hosting, Vercel, Netlify)  

---

## 🔧 Firebase Setup

### 1. Create Firebase Project
Go to [Firebase Console](https://console.firebase.google.com/) and create a project.

### 2. Enable Services
- **Authentication** → Enable **Anonymous sign-in**  
- **Firestore Database** → Create database in test mode (then apply rules below)  
- **Cloud Messaging** → Generate keys for push notifications  

### 3. Add Firebase Config
Replace your config in `index.html`:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "your-sender-id",
  appId: "your-app-id"
};
