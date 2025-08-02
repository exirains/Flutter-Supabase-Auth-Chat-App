# Flutter Supabase Auth & Chat App

![App Demo](https://github.com/user-attachments/assets/40ad0079-763e-496d-8cd6-a9ca6e5d301d)  

<div align="center">
  <a href="https://drive.google.com/drive/folders/1Sew60kyhkBJLkgmS-P2CcpGT-TooQQUf?usp=sharing">
    <img src="https://img.shields.io/badge/Download_APK-Android-green?logo=android&style=for-the-badge" alt="Download APK">
  </a>
  
  <a href="https://drive.google.com/drive/folders/1cozNLxqT6OIHCa9zEGup-3bQn5hpKhNb?usp=sharing">
    <img src="https://img.shields.io/badge/Download_Source-ZIP-blue?logo=github&style=for-the-badge" alt="Download Source">
  </a>
</div>

A Flutter application featuring secure authentication, real time messaging, and user profile management powered by Supabase's backend.

## 🌟 Key Features

### 🔒 Secure Authentication
- Email/password signup & login flows
- Session management with Supabase Auth
- Protected routes implementation

### 💬 Real-Time Chat
- Instant message updates using Supabase Realtime
- Optimized message streaming
- Clean chat interface with message history

### 👤 User Profiles
- Editable profile information
- Profile picture uploads (Supabase Storage)
- Persistent user preferences

### 🎁 Reward System
- Daily check-in rewards
- 24-hour cooldown timer
- Reward history tracking

## 🛠 Tech Stack

| Category       | Technologies Used |
|---------------|-------------------|
| **Frontend**  | Flutter 3.x • Dart 3.x |
| **Backend**   | Supabase (Auth • Realtime • Storage) |
| **Tools**     | Android Studio • VS Code • Git |

## 📦 Packages Used
```yaml
dependencies:
  flutter:
    sdk: flutter
  supabase_flutter: ^2.9.1
  image_picker: ^1.1.2
  cupertino_icons: ^1.0.8
  cached_network_image: ^3.4.1
