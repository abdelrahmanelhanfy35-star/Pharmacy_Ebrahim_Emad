# Ibrahim & Emad Pharmacy Management System (صيدلية إبراهيم وعماد)

A premium, professional-grade desktop application for pharmacy management, built with **React**, **Vite**, **Electron**, and **Dexie/Realm**. This application features a high-end Apple-inspired glassmorphic UI, bilingual receipt printing, and advanced profit tracking.

## ✨ Features

- **Premium UI/UX**: Apple-inspired design with glassmorphism, smooth transitions, and micro-animations.
- **Bilingual Receipts**: Automated Arabic and English receipt generation optimized for 80mm thermal printers.
- **Advanced Inventory**: Mandatory purchase price tracking for accurate profit calculation and supplier linking.
- **Smart Dashboard**: Real-time sales charts, top-selling analytics, and instant business health stats.
- **Safety Alerts**: Global notification system for near-expiry medicines and low-stock warnings.
- **Offline First**: Robust local database management using Dexie (Dev) and Realm (Production).
- **Supplier Management**: Full module for managing medical companies and suppliers.

## 🛠 Tech Stack

- **Frontend**: React.js, Lucide Icons, Vanilla CSS (Glassmorphism).
- **Database**: Dexie.js (IndexedDB) for browser, Realm DB for Electron desktop.
- **Desktop Wrapper**: Electron.js.
- **Build Tool**: Vite.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/USER_NAME/ibrahim-emad-pharmacy-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ibrahim-emad-pharmacy-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running Locally (Browser)
To start the development server for web testing:
```bash
npm run dev
```

### Running Desktop Version (Electron)
To run the app in a local Electron window:
```bash
npm run start
```

### Building for Production
To create a Windows installer (`.exe`):
```bash
npm run electron:build
```

## 📄 License
This project is for private use by **Ibrahim & Emad Pharmacy**.

## 👨‍💻 Developed By
Antigravity AI (Google Deepmind)
