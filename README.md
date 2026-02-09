# 💖 CUK Commit — From Campus to Connection

**CUK Commit** is a university-focused social matching platform built for students of **Central University of Karnataka (CUK)**.  
It is designed to encourage **meaningful interactions** — relationships, friendships, and genuine campus connections — in a structured and verified environment.

> 🎯 Goal: Enable safe, real student connections within campus.

---

## ✨ Key Features

### 🔐 Authentication
- Email & Password login/signup  
- Email verification  
- Forgot / Reset password  
- Google Sign-In (OAuth) via Supabase  

### 🧑‍🎓 Verified Student Profiles
- Student-based account system  
- Mandatory onboarding before discovery access  
- Profile completion validation  

### 🧾 Onboarding Flow
- Basic profile setup (name, gender, etc.)  
- Interest selection  
- Bio creation  
- Profile photos upload  

### 📸 Photo System
- 6-slot grid layout  
- Add / remove photo  
- Upload progress per slot  
- Powered by Supabase Storage  

### ❤️ Discovery & Matching
- Discover page for viewing profiles  
- Real-time online status  
- Matching system foundation (expanding)  

---

## 🧱 Tech Stack

### Frontend
- Flutter  
- Provider (state management)  
- Custom reusable UI components  

### Backend
- Supabase  
  - Authentication  
  - PostgreSQL Database  
  - Storage  

---

## 🗂️ Project Structure

```bash
lib/
├── core/
│   ├── constants/
│   ├── routes/
│   ├── services/
│   └── widgets/
├── features/
│   ├── auth/
│   ├── onboarding/
│   ├── matching/
│   └── splash/
├── auth_gate.dart
└── main.dart
