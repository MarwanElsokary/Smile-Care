# 😁 Smile Care — AI‑Powered Dental Case Management App

A modern **Flutter application** built to help **dentistry students** find and treat real medical cases with the help of **doctors, supervisors, and AI diagnosis**. The app leverages **Firebase** for full data management and **Flask AI backend** for case image classification.

[![Flutter](https://img.shields.io/badge/Flutter-3.24-blue?logo=flutter)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Integrated-orange?logo=firebase)](https://firebase.google.com)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-MarwanElsokary%2FSmile--Care-black?logo=github)](https://github.com/MarwanElsokary/Smile-Care)

---

## 🦷 Overview

**Smile Care** is a medical education platform that connects dental students, doctors, and supervisors.
Doctors can upload cases with diagnostic details, students can request cases for treatment, and supervisors approve or reject the cases.
Additionally, an **AI system built with Flask** analyzes case images to assist in diagnosis.

---

## 📱 Features

* 🔐 Firebase Authentication (login/register by role)
* 👨‍⚕️ **Three user roles** — Student, Doctor, Supervisor
* 📤 Doctors upload cases with image, description, and category
* 🧠 **AI diagnosis** integration (Flask API + TensorFlow Lite)
* 📩 Students send requests to treat cases
* ✅ Supervisors approve or reject requests
* 📸 Image compression before upload (using `flutter_image_compress`)
* 🔔 Push notifications (Firebase Messaging)
* 🧭 Onboarding with local Hive storage
* 🧱 Clean Architecture (Data, Domain, Presentation layers)
* 💾 Firebase Firestore & Storage integration
* 💬 Toasts, carousels, and responsive design

---

## 🧠 Tech Stack

* **Frontend:** Flutter (Dart)
* **Backend:** Flask (Python)
* **Database:** Firebase Firestore
* **Storage:** Firebase Storage
* **Auth:** Firebase Authentication
* **State Management:** Bloc / Cubit
* **Local Storage:** Hive
* **Networking:** Dio
* **ML:** TensorFlow Lite + Flask AI endpoint

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK (>=3.0)
* Android Studio / VS Code
* Firebase project configured (Auth, Firestore, Storage)
* Flask backend for AI running locally or via Ngrok

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MarwanElsokary/Smile-Care.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Smile_care
    ```

3. Install dependencies:
    ```bash
    flutter pub get
    ```

4. Run the app:
    ```bash
    flutter run
    ```

### Testing

1. Run the app:

    ```bash
    flutter test
    ```


If Firebase isn’t set up yet, add your configuration files:

* `android/app/google-services.json`
* `ios/Runner/GoogleService-Info.plist`

---

## 🤝 Contributing

- Fork the repo

- Create your feature branch (git checkout -b feature/YourFeature)

- Commit changes (git commit -m 'Add some feature')

- Push to branch (git push origin feature/YourFeature)

- Open a Pull Request
---

## 👨‍💻 Author

**Marwan Yasser ElSokary**
Flutter Developer
[GitHub Profile](https://github.com/MarwanElsokary)

---


> 🪄 *Smile Care — bridging dental education, technology, and AI for better smiles.*


