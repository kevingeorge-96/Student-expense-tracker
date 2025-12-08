# 💸 Budgettt - The Ultimate Student Money Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Status: Stable](https://img.shields.io/badge/Status-Stable-success)
![Platform: PWA](https://img.shields.io/badge/Platform-PWA%20%2B%20Archive-blue)

**Secure. Offline-First. Privacy-Focused.**  
A lightning-fast budgeting tool designed specifically for Indian Students to track every Rupee without data leaching.

---

## ✨ Features that Wow

- **📱 User-First Design**: Minimalist Dark Mode UI that feels premium and fast.
- **⚡ 100% Offline Capable**: Built with **IndexedDB**. Works perfectly without internet.
- **☁️ Optional Cloud Sync**: Login only when you want to backup/sync across devices via **Firebase**.
- **🧩 Companion Chrome Extension**: Quick-add expenses while browsing without opening the app.
- **🔒 Privacy Core**: Your data stays on your device until YOU decide to sync.

---

## 🚀 Getting Started (Web PWA)

1. **Launch**: Open `web-pwa/index.html` in your browser.
2. **Install**: Click the "Install" button in your browser address bar to use it like a native app.
3. **Usage**:
   - **Offline Mode**: Start adding transactions immediately.
   - **Sync**: Login with Email/Password to enable cloud backup.

---

## 🧩 Chrome Extension Setup

1. Open Chrome and navigate to `chrome://extensions`.
2. Enable **Developer Mode** (Toggle in top right).
3. Click **Load Unpacked**.
4. Select the `chrome-extension` folder from this project.
5. **Pin it!** Click the extension icon to instantly add transactions (e.g., "Food", "Fun") without leaving your tab.

---

## 🛠️ Tech Stack & Architecture

Built with pure **Vanilla Web Technologies** for maximum performance and zero bloat.

- **Frontend**: HTML5, CSS3, ES6 JavaScript (No Frameworks!).
- **Storage**:
  - Local: `IndexedDB` (Browser Native DB).
  - Cloud: `Firebase Firestore` (Encrypted & Secure).
- **Core Engine**: Shared logic module (`/core`) used by both PWA and Extension.
- **Math**: Integer-based arithmetic (Paise) for zero floating-point errors. `₹100.00` = `10000` paise.

---

## 👩‍💻 For Developers

The project uses a **Shared Core Architecture**:

- `/core`: The brain. Contains DB wrappers, Auth, and Sync logic.
- `/web-pwa`: The main Progressive Web App interface.
- `/chrome-extension`: Lightweight popup interface. Note: It contains a copy of `/core` for strict sandbox compliance.

**Repository**: [https://github.com/TarunyaProgrammer/Student-expense-tracker.git](https://github.com/TarunyaProgrammer/Student-expense-tracker.git)

---

_Made with ❤️ for students who want financial freedom._
