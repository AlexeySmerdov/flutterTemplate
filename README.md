# Flutter Firebase Template

🚀 A scalable and modular Flutter project template with:

- ✅ Firebase Core & Authentication
- ✅ Riverpod for state management
- ✅ GoRouter for navigation
- ✅ Feature-based folder structure

## 🔧 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/flutterTemplate.git
cd flutterTemplate
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Configure Firebase

- Create a project in [Firebase Console](https://console.firebase.google.com)
- Add Android/iOS/Web app
- Download `google-services.json` into `android/app/`
- (For iOS) Add `GoogleService-Info.plist` into `ios/Runner/`

### 4. Run the app

```bash
flutter run
```

## 🗂 Project Structure

```
lib/
├── main.dart
├── app.dart
├── core/
│   ├── constants/
│   └── services/
├── features/
│   ├── auth/
│   └── home/
├── router/
└── models/ (optional)
```

## 🔥 Firebase

Includes Firebase initialization and anonymous login. Easily extend to support email/password or Google sign-in.

---

MIT License © 2025 Alexey Smerdov