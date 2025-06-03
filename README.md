# 🌐 Anuvadham - Real-Time Translation Web App

Anuvadham is a modern, minimalistic, and responsive real-time translation platform designed to enable seamless multilingual communication using voice or text input. Built with a secure, scalable, and accessible architecture, Anuvadham is ideal for travelers, professionals, and users with speech limitations.

## 🚀 Features

- 🔊 Real-time speech and text translation
- 📂 Conversation history with search and filter options
- 🧑‍💼 User authentication 
- 🖼️ Profile management 
- 🎙️ Voice input with animated pitch-based UI
- 📝 Text editor for manual input
- ☁️ Cloudinary-based audio/image storage
- 🔐 JWT-based secure authentication

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: React (Vite)
- **Styling**: CSS Modules / Styled Components
- **Audio & Speech**: Web Speech API

### Backend
- **Framework**: Node.js + Express.js
- **Database**: MongoDB Atlas
- **Storage**: Cloudinary (audio/image)
- **Authentication**: JWT, bcrypt

### External APIs
- Google Translate API
- Google Speech-to-Text API
- Google Text-to-Speech API

---

## 🧑‍💻 Pages & Functionality

### `/` Home Page
- Recent conversations summary
- Navigation links: Translate, History, Profile, Login, Register

### `/login`, `/register`
- Secure login, register

### `/translate`
- Pre-conversation setup: purpose, name, languages, input methods
- Real-time translation interface with:
  - Live captions
  - Start/Stop session controls
  - Exit flow with download/cancel prompt

### `/history`
- Card-based design with:
  - Source/target text
  - Languages and timestamps
  - Search, filter, bulk delete
  - Audio playback and export options

### `/profile`
- Profile picture, name, email
- Change password and logout

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/anuvadham.git
cd anuvadham
