# FlutterAuth – Login & Registration App

A clean and modern authentication mobile application built with **Flutter**. FlutterAuth provides seamless user registration and login functionality with form validation and an intuitive UI.

Developed as a **Final Year University Project** to showcase Flutter fundamentals, responsive UI design, and authentication workflows.

---

## 📱 Features

- User Registration with validation
- Secure User Login
- Real-time Form Validation
- Clean & Intuitive UI
- Android Support
- Production-Ready APK

---

## 🛠️ Tech Stack

- **Flutter** - UI Framework
- **Dart** - Programming Language
- **Material Design** - UI Components
- **Firebase** - Authentication & Backend (optional)
- **Android SDK** - Native Support

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (v3.0+)
- Dart SDK
- Android Studio or VS Code with Flutter extension
- Android Device or Emulator
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flutter-auth-app.git
   cd flutter-auth-app
   ```

2. Install dependencies:
   ```bash
   flutter clean
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

### 📦 Build Release APK

To generate a release APK for submission:

```bash
flutter build apk --release
```

The APK will be generated at:
```
build/app/outputs/flutter-apk/app-release.apk
```

---

## 📁 Project Structure

```
lib/
├── main.dart              # App entry point
├── screens/               # UI screens
│   ├── login_screen.dart
│   └── register_screen.dart
├── services/              # Business logic
│   └── auth_service.dart
└── firebase_options.dart  # Firebase configuration
```

---

## 🔐 Authentication

The app supports Firebase authentication. To set up Firebase:

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com)
2. Add Android app to your Firebase project
3. Download `google-services.json` and place it in `android/app/`
4. Update `lib/firebase_options.dart` with your Firebase credentials

For detailed setup, see [FIREBASE_SETUP.md](FIREBASE_SETUP.md)

---

## 📝 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

Developed by [Your Name]

For questions or feedback, feel free to reach out or open an issue.