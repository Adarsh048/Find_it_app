# 🔍 Find_it

Find_it is an AI-powered search application inspired by Perplexity AI. It combines a modern Flutter frontend with a FastAPI backend to provide intelligent, conversational search results in a clean and responsive interface.

---

## ✨ Features

- 🤖 AI-powered conversational search
- 💬 Real-time responses
- 📝 Markdown formatted answers
- ⚡ Fast and responsive UI
- 📱 Cross-platform support 
- 🎨 Modern Material Design interface
- 🔄 Loading skeleton animations for better user experience

---

## 🛠️ Tech Stack

### Frontend
- Flutter
- Dart
- Material Design
- Flutter Markdown
- Google Fonts
- WebSocket Client
- Skeletonizer

### Backend
- FastAPI
- Python
- AI Model Integration
- REST APIs

---

## 📂 Project Structure

```
Find_it/
│
├── lib/                 # Flutter application
├── android/             # Android configuration
├── ios/                 # iOS configuration
├── web/                 # Web support
├── windows/             # Windows support
├── macos/               # macOS support
├── linux/               # Linux support
└── server/              # FastAPI backend
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/Find_it.git
cd Find_it
```

### Install Flutter Dependencies

```bash
flutter pub get
```

### Run the Flutter App

```bash
flutter run
```

---

## Backend Setup

Navigate to the server directory:

```bash
cd server
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
fastapi dev main.py
```

or

```bash
uvicorn main:app --reload
```

---

## 📱 Supported Platforms

- ✅ Android
- ✅ iOS
- ✅ Windows
- ✅ Linux
- ✅ macOS
- ✅ Web

---


## 🎯 Future Improvements

- Voice Search
- Search History
- User Authentication
- Dark/Light Theme Toggle
- AI Chat Memory
- Image Search
- File Upload Support
- Multi-language Support

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub. It helps support future development!

---

## 📄 License

This project is licensed under the MIT License.
