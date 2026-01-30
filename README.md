# ⚡ Unbreakfocus

**A minimalist, distraction-free study timer designed for high-stakes aspirants (JEE/NEET/Boards).**

> "Minimalism meets discipline. No distractions, just pure focus."

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 📱 About The Project

**Unbreakfocus** is not just another timer; it is a discipline engine. Built for students who cannot afford to waste time, it features a "Glass" UI aesthetic (Pure Black + Neon Cyan) and runs 100% offline.

Unlike standard timers that stop when you switch apps, **Unbreakfocus features "YouTube Catch-up" logic**—it intelligently calculates the time difference when you return from watching a video lecture and adds it to your session instantly.

## ✨ Key Features

*   **The Engine (Timer):** A countdown timer that shifts into "Overtime Mode" (counting up) when the goal is reached, encouraging flow state.
*   **YouTube Catch-up Logic:** Uses `WidgetsBindingObserver` to track background time, allowing students to watch lectures without stopping the timer.
*   **Consistency Heatmap:** A GitHub-style contribution grid to visualize study consistency over the last 30 days.
*   **Streak Flame:** Gamified streak counter to maintain daily momentum.
*   **100% Offline Persistence:** Uses `shared_preferences` with custom JSON mapping to save all data locally. No login or internet required.
*   **Glassmorphism UI:** A sleek, dark-themed UI designed to reduce eye strain during late-night study sessions.

## 🛠️ Tech Stack

*   **Framework:** Flutter (Dart)
*   **State Management:** `setState` + `WidgetsBindingObserver` (Lifecycle management)
*   **Persistence:** `shared_preferences` (JSON Serialization)
*   **Notifications:** `flutter_local_notifications`
*   **UI Assets:** `cupertino_icons`, `google_fonts`

## 📸 Screenshots

| Dashboard | The Engine | Stats & Heatmap |
|:---:|:---:|:---:|
| <img src="path/to/dashboard.png" width="200"> | <img src="path/to/timer.png" width="200"> | <img src="path/to/stats.png" width="200"> |

## 🚀 How to Install (APK)

1.  Go to the [Releases](https://github.com/jhakumarshekhar11/unbreakfocus/releases) section of this repository.
2.  Download the latest `Unbreakfocus.apk`.
3.  Install it on your Android device (Allow installation from unknown sources).

## 💻 How to Run Locally

Prerequisites: Flutter SDK installed.

# Clone the repository
git clone https://github.com/jhakumarshekhar11/unbreakfocus.git

# Navigate to the directory
cd unbreakfocus

# Install dependencies
flutter pub get

# Run the app
flutter run
👨‍💻 Author
Shekhar Kumar Jha
Portfolio: shekharkumarjha.onrender.com
GitHub: @jhakumarshekhar11
If you find this project useful, please give it a star ⭐️!
***
