# Firebase Setup Guide

## Step 1: Get Dependencies
Run this command in your project root:
```bash
flutter pub get
```

## Step 2: Create Firebase Project
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Click "Create a project"
3. Enter project name and follow the setup wizard
4. Enable Authentication (Email/Password)

## Step 3: Configure Firebase for Android
1. In Firebase Console, go to Project Settings
2. Download `google-services.json` for Android
3. Place it in `android/app/` directory

## Step 4: Configure Firebase for iOS
1. In Firebase Console, download `GoogleService-Info.plist` for iOS
2. Open `ios/Runner.xcworkspace` in Xcode
3. Add the plist file to the Runner project

## Step 5: Update firebase_options.dart
1. Go to Firebase Console → Project Settings
2. Copy your project credentials
3. Update `lib/firebase_options.dart` with your credentials:
   - apiKey
   - appId
   - messagingSenderId
   - projectId
   - authDomain (for web)
   - storageBucket

## Step 6: Run the App
```bash
flutter run
```

## Troubleshooting

### Flutter command not found
- Make sure Flutter is in your PATH
- Run `flutter doctor` to check installation

### Firebase initialization error
- Verify firebase_options.dart has correct credentials
- Check that google-services.json is in android/app/

### Build errors on Android
- Run `flutter clean`
- Run `flutter pub get`
- Run `flutter run`

### Build errors on iOS
- Run `flutter clean`
- Run `cd ios && pod install && cd ..`
- Run `flutter run`
