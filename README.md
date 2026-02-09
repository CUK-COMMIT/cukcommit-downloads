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
````



## 🔄 App Flow

**Splash → Auth Gate → Correct Screen**

| User State                     | Destination     |
| ------------------------------ | --------------- |
| Not logged in                  | Welcome / Login |
| Logged in + incomplete profile | Onboarding      |
| Logged in + complete profile   | Discover        |

---

## 🔗 Deep Linking

```
com.app.cukcommit://login-callback/
com.app.cukcommit://reset-password/
```

---

## 🚀 Setup

### Clone

```bash
git clone <repo-url>
cd cuk_commit
```

### Install dependencies

```bash
flutter pub get
```

### Environment file

Create `.env`:

```env
SUPABASE_URL=your_url
SUPABASE_ANON_KEY=your_key
```

### Run

```bash
flutter run
```

---

## 🔑 Supabase Checklist

* Enable Email Auth
* Enable Google OAuth
* Add redirect URLs
* Create storage bucket for user photos

---

## 🔐 Security

* Keys not committed
* Environment-based configuration
* Auth handled by Supabase

---

## 🛠 Planned Improvements

* Advanced match algorithm
* Filters (year, department, interests)
* Full chat system
* Moderation & reporting tools
* Profile verification badges

---

## 📄 License

**Not Open Source — All Rights Reserved**

Unauthorized copying, modification, distribution, or reuse is prohibited.

---


## 👥 Team Members

| Profile | Name |
|--------|------|
| <img src="https://github.com/Uni-Creator.png" width="80" height="80" style="border-radius:50%"/> | **[Abhay Singh](https://github.com/Uni-Creator)** <br/> 
| <img src="https://github.com/Droid-DevX.png" width="80" height="80" style="border-radius:50%"/> | **[Ayush Tandon](https://github.com/Droid-DevX)** <br/>
| <img src="https://github.com/abhaydwived.png" width="80" height="80" style="border-radius:50%"/> | **[Abhay Dwivedi](https://github.com/abhaydwived)** <br/> 
---
