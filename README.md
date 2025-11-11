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

```bash
git clone https://github.com/MarwanElsokary/Smile-Care.git
cd Smile-Care
flutter pub get
flutter run
```

If Firebase isn’t set up yet, add your configuration files:

* `android/app/google-services.json`
* `ios/Runner/GoogleService-Info.plist`

---


## 🖼️ Screenshots

<p align="center">
  <img src="assets/screenshots/login.png" alt="Login Screen" width="22%" />
  <img src="assets/screenshots/doctor_home.png" alt="Doctor Home" width="22%" />
  <img src="assets/screenshots/add_case.png" alt="Add Case" width="22%" />
  <img src="assets/screenshots/ai_diagnosis.png" alt="AI Diagnosis" width="22%" />
</p>

---

## 🤝 Contributing

1. Fork the repo
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a Pull Request

---

## 👨‍💻 Author

**Marwan Yasser ElSokary**
Flutter Developer
[GitHub Profile](https://github.com/MarwanElsokary)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

> 🪄 *Smile Care — bridging dental education, technology, and AI for better smiles.*

