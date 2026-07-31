<div align="center">

# 🎓 Away Scholars
### **Advanced Academic & Documentation Management System**

[![Platform](https://img.shields.io/badge/Platform-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Database](https://img.shields.io/badge/Database-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![UI](https://img.shields.io/badge/Design-Material_3-757575?style=for-the-badge&logo=material-design&logoColor=white)](https://m3.material.io/)

**A premium, robust platform for managing student profiles, academic journeys, and complex financial audits.**

---

[Explore Features](#-key-features) • [Architecture](#-architecture) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Away Scholars** is a specialized management system designed to handle the intricate documentation and financial auditing required for academic consultancy and student processing. Built with **Flutter** and **SQLite**, it provides a high-performance, offline-capable experience with a focus on data integrity, professional reporting, and a modern, glassmorphic UI/UX.

---

## ✨ Key Features

### 📂 Student Lifecycle Management
- **Comprehensive Profiles:** Manage personal details, contact info, and entry dates with automated ID generation checks.
- **Academic Stepper:** Track progress through stages (New → Processing → Filed → Approved) using a visual progress indicator.
- **Visual Timeline:** Log operational notes and history with a connected vertical timeline for every student.

### 💰 Professional Financial Audit
- **Service Billing:** Detailed breakdown of service fees (Admission, Visa, File Processing, etc.).
- **Payment History:** Robust transaction logging with support for various payment methods.
- **Real-time Calculations:** Automated tracking of **Net Receivable**, **Total Received**, and **Balance Due**.

### 📄 Enterprise Reporting
- **Individual Ledgers:** Generate professional individual student ledgers with watermarks and brand footers.
- **Summary Insights:** Export full system reports in both **PDF** and **CSV** formats.
- **Dashboard Analytics:** High-fidelity charts showing revenue trends, status distribution, and collection health.

### 🎨 Modern UI/UX
- **Glassmorphism:** Elegant semi-transparent cards with backdrop blur effects.
- **Dark Mode Support:** Fully dynamic theme switching for all screens.
- **Staggered Animations:** Premium list animations and micro-interactions for a fluid user experience.

---

## 📁 Project Structure

The application follows a modular architecture for scalability and maintainability:

```text
lib/
├── 🛠️ core/          # Business logic engines (e.g., PDF Generator)
├── 📦 models/        # Data entities (Student, User, Payment, etc.)
├── 🧬 providers/     # State management (Provider) for Auth & Students
├── 📱 screens/       # Feature-specific UI (Dashboard, Ledger, Details)
├── 🔌 services/      # Persistence layer (SQLite / DatabaseService)
└── 🧩 widgets/       # Reusable UI components (CustomCard, StatusBadge)
```

---

## 🏗️ Architecture

- **State Management:** `Provider` for reactive UI updates and dependency injection.
- **Database:** `sqflite` (SQLite) with a Clear-and-Insert transaction strategy to ensure zero data duplication.
- **Navigation:** Deep linking and Hero animations for seamless transitions between screens.
- **Security:** Persistent authenticated sessions with encrypted-style mock logic and shared preference storage.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Framework** | Flutter (SDK 3.x) |
| **Language** | Dart |
| **Persistence** | SQLite (`sqflite`), `shared_preferences` |
| **State Mgmt** | `provider` |
| **Graphics** | `fl_chart` (Analytics), `shimmer` (Loading) |
| **Documents** | `pdf`, `printing`, `csv` |
| **Sharing** | `share_plus` |

---

## 🚀 Getting Started

### 1. Prerequisites
- Flutter SDK installed and configured.
- Android/iOS device or emulator.

### 2. Installation
```bash
# Clone the repository
git clone https://github.com/fuadk/away_scholars.git

# Install dependencies
flutter pub get

# Run the app
flutter run
```

### 3. Authentication (Default Credentials)
| Field | Value |
| :--- | :--- |
| **User ID** | `awayscholars` |
| **Password** | `Away666` |

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Away Scholars</i>
