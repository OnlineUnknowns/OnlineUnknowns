# Booking Appointment System

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=1000&color=00D4FF&center=true&vCenter=true&width=1000&lines=AI-Powered+Visa+Appointment+Automation;Real-Time+Slot+Detection+and+Instant+Booking;VFS+Global+%7C+BLS+International+%7C+TLScontact;Desktop+App+%7C+Admin+Dashboard+%7C+Telegram+Alerts)](https://git.io/typing-svg)

<br/>

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-Automation-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Eel](https://img.shields.io/badge/Eel-Desktop_GUI-FF6F00?style=for-the-badge&logo=googlechrome&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Admin_Panel-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-Instant_Alerts-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![License](https://img.shields.io/badge/License-Key_Activation-8B5CF6?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production_Ready-00FF88?style=for-the-badge)

<br/>

<a href="https://www.linkedin.com/in/onlineunknown/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://wa.me/201286016083" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-Support-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>
<a href="https://buymeacoffee.com/onlineunknowns" target="_blank">
  <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-Support-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=000000"/>
</a>

</div>

---

## 📖 Overview

**Smart Appointment Booking System** is a professional desktop automation platform designed to monitor and book visa appointments automatically across major providers such as:

- 🌍 VFS Global
- 🏢 BLS International
- 🇫🇷 TLScontact
- 🇮🇹 Prenotami
- 🇮🇹 Almaviva

The system continuously checks for appointment availability, sends instant Telegram alerts, and completes the booking process automatically the moment a slot becomes available.

Built specifically for:

- Visa agencies
- Immigration consultants
- Travel offices
- Power users managing multiple applicants

---

## ✨ Core Features

### ⚡ Real-Time Slot Detection
Monitors appointment portals 24/7 and reacts within seconds when a slot appears.

### 🤖 Automatic Booking
Completes the full booking workflow without manual intervention.

### 🧠 CAPTCHA Solving
Supports external providers like 2Captcha and CapSolver.

### 🔄 Proxy Rotation
HTTP and SOCKS5 proxy pools with automatic health checks.

### 📲 Telegram Notifications
Receive instant alerts when slots are found or booked.

### 👥 Multi-Profile Management
Store and manage unlimited applicant profiles.

### 🔑 License Activation
Secure machine-based license validation.

### 🖥️ Desktop GUI
Modern desktop application built with Eel + TailwindCSS + GSAP.

### 📊 Admin Dashboard
Live monitoring panel available at `http://localhost:5000`.

### 🔁 Auto Updates
One-click update system.

---

## 🌍 Supported Platforms

| Platform | Description |
|--------|--------|
| VFS Global | Global visa appointment outsourcing platform |
| BLS International | Visa and consular services |
| TLScontact | European visa appointment platform |
| Prenotami | Official Italian consulate booking portal |
| Almaviva | Italian visa center booking system |

---

## 🌐 Supported Countries

- Egypt
- Morocco
- Algeria
- Tunisia
- Senegal
- Saudi Arabia
- UAE
- Pakistan
- Bangladesh
- India
- Turkey
- Italy

---

## 🏗️ System Architecture

```text
Desktop GUI (Eel + TailwindCSS + GSAP)
            │
            ▼
Python Core Engine
 ├── Monitor Engine
 ├── Booking Engine
 ├── Proxy Manager
 ├── CAPTCHA Solver
 ├── Scheduler
 ├── License Manager
 └── Telegram Notifier
            │
            ▼
Platform Adapters
 ├── VFS Global
 ├── BLS International
 ├── TLScontact
 ├── Prenotami
 └── Almaviva
            │
            ▼
SQLite Database
            │
            ▼
Flask Admin Dashboard
````

---

## 🛠️ Tech Stack

| Layer              | Technology           |
| ------------------ | -------------------- |
| Core Language      | Python 3.12          |
| Browser Automation | Playwright           |
| Desktop GUI        | Eel                  |
| Styling            | TailwindCSS          |
| Animation          | GSAP                 |
| Admin Panel        | Flask                |
| Database           | SQLite               |
| Notifications      | Telegram Bot API     |
| Scheduling         | APScheduler          |
| Packaging          | PyInstaller          |
| CAPTCHA Solving    | 2Captcha / CapSolver |
| Proxy Management   | Custom Rotator       |

---

## 📁 Project Structure

```text
smart-booking-system/
├── main.py
├── core/
│   ├── monitor.py
│   ├── booker.py
│   ├── captcha.py
│   ├── proxy_manager.py
│   ├── notifier.py
│   ├── scheduler.py
│   └── license.py
│
├── platforms/
│   ├── vfs/
│   ├── bls/
│   ├── tls/
│   ├── prenotami/
│   └── almaviva/
│
├── admin/
│   ├── app.py
│   ├── routes/
│   └── templates/
│
├── web/
│   ├── index.html
│   ├── css/
│   └── js/
│
├── database/
│   ├── schema.sql
│   └── db.py
│
├── assets/
│   ├── icons/
│   └── screenshots/
│
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/your-org/smart-booking-system.git
cd smart-booking-system

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

playwright install chromium firefox webkit

npm install
npm run build:css

python scripts/init_db.py

python main.py
```

---

## ▶️ Quick Start

1. Launch the application.
2. Activate your license key.
3. Create applicant profiles.
4. Select target platform and country.
5. Configure Telegram alerts.
6. Add proxies (optional).
7. Click **Start Monitoring**.

When a slot is detected:

* Telegram alert is sent.
* Booking starts automatically.
* Confirmation number is saved.

---

## 📊 Admin Dashboard

Access the management dashboard:

```text
http://localhost:5000
```

### Dashboard Features

* Live session monitoring
* Slot statistics
* Applicant profiles
* Proxy management
* Logs viewer
* License information
* Update manager

---

## 📸 Screenshots

| Dashboard                             | Profiles                             | Proxy Manager                       |
| ------------------------------------- | ------------------------------------ | ----------------------------------- |
| ![](assets/screenshots/dashboard.png) | ![](assets/screenshots/profiles.png) | ![](assets/screenshots/proxies.png) |

| Slot Alert                             | Admin Panel                             | Telegram Notification                      |
| -------------------------------------- | --------------------------------------- | ------------------------------------------ |
| ![](assets/screenshots/slot-alert.png) | ![](assets/screenshots/admin-panel.png) | ![](assets/screenshots/telegram-alert.png) |

---

## 🔐 License System

```text
Format: SABS-XXXX-XXXX-XXXX-XXXX
```

Features:

* Hardware fingerprint binding
* Online activation
* Offline grace period
* Secure validation

---

## 📲 Telegram Integration

Receive alerts for:

* Slot found
* Booking success
* Booking failure
* License expiration
* System updates

---

## 🔧 Troubleshooting

### Playwright Issues

```bash
playwright install --with-deps chromium firefox webkit
```

### Telegram Not Working

Verify bot token and chat ID.

### License Activation Failed

Check internet connection and system clock.

### Admin Dashboard Not Loading

Ensure port `5000` is available.

---

## 🤝 Support

* 💼 LinkedIn: [https://www.linkedin.com/in/onlineunknown/](https://www.linkedin.com/in/onlineunknown/)
* 💬 WhatsApp: [https://wa.me/201286016083](https://wa.me/201286016083)
* ☕ Buy Me a Coffee: [https://buymeacoffee.com/onlineunknowns](https://buymeacoffee.com/onlineunknowns)

---

## 📄 License

This project is proprietary software.

Unauthorized copying, modification, redistribution, or reverse engineering is prohibited without written permission.

---

<div align="center">

### 🚀 Built for Speed. Designed for Reliability. Engineered for Automation.

**Made with ❤️ by OnlineUnknowns**

</div>
```
