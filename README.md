Flutter Chat Demo
This repository contains a demo chat application built with Flutter, showcasing the capabilities of Flutter in creating a cross-platform chat app.

Features
Cross-Platform Compatibility: Supports Android, iOS, web, macOS, and Windows.
Real-Time Messaging: Send and receive text messages, images, and stickers in real-time.
User Authentication: Log in using third-party services such as Google or Firebase.
User Profiles: Update user profiles and avatars.
Push Notifications: Receive notifications for new messages.

Screenshots
![chatscreen](https://github.com/user-attachments/assets/f5afb8c4-e09b-417d-9dcd-37561c641f6e)
![homescreen](https://github.com/user-attachments/assets/98ba0cbd-5446-479d-8962-b9494ae5a2e9)
![settingscreen](https://github.com/user-attachments/assets/22e42126-950e-4571-8b58-b35dfed51abe)

Getting Started
Follow these steps to get the project up and running on your local machine.

Prerequisites
Flutter 3.0.0 or later
Android Studio 3.5 or later / Xcode 11.0 or later
Installation

Clone the repository:
git clone https://github.com/nchola/flutter-chat-demo.git
cd flutter-chat-demo

Clean the project:
flutter clean

Install dependencies:
flutter pub get
Running the App

For mobile platforms (Android/iOS):
flutter run

For web:
Navigate to the web/ directory and install the required JavaScript dependencies:
cd web
npm install
flutter run -d chrome

Configuration
Replace the placeholders in the command with your actual SDKAppID and KEY:
flutter run --dart-define=SDK_APPID={YOUR_SDKAPPID} --dart-define=KEY={YOUR_KEY}

Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

