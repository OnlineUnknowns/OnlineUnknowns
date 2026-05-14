<!-- BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.12"/>
  <img src="https://img.shields.io/badge/Eel-GUI-FF6F00?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Eel"/>
  <img src="https://img.shields.io/badge/Playwright-Automation-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/TailwindCSS-Styling-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="TailwindCSS"/>
  <img src="https://img.shields.io/badge/GSAP-Animation-88CE02?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP"/>
  <img src="https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Telegram-Alerts-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram API"/>
  <img src="https://img.shields.io/badge/PyInstaller-Packager-3670A0?style=for-the-badge&logo=python&logoColor=white" alt="PyInstaller"/>
</p>

---

# 🤖 Smart Appointment Booking Bot

> **Enterprise-grade desktop automation for VFS, BLS, and TLS visa appointment platforms.**  
> Detect open slots the moment they appear — and book them before anyone else.

<p align="center">
  <a href="https://www.linkedin.com/in/onlineunknown/" target="_blank">🔗 LinkedIn</a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://buymeacoffee.com/onlineunknowns" target="_blank">☕ Buy Me a Coffee</a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://wa.me/201286016083" target="_blank">💬 WhatsApp Support</a>
</p>

---

## 📖 Overview

**Smart Appointment Booking Bot** is a production-ready, enterprise desktop application that continuously monitors visa appointment platforms (VFS Global, BLS International, TLS Contact) and **automatically books available slots** the instant they become free.

Built for immigration consultants, visa agencies, and individual applicants who cannot afford to miss a critical appointment window. The bot operates silently in the background — rotating proxies, solving CAPTCHAs, navigating multi-step booking flows — and fires an instant Telegram notification the moment a slot is secured.

The application ships as a single-file Windows installer and includes a polished web-based admin panel, license activation system, and multi-account management — everything needed to operate at scale.

---

## ✨ Features

- 🌐 **Multi-Browser Automation** — Powered by Playwright; supports Chromium, Firefox, and WebKit with configurable stealth profiles
- 🔍 **Real-Time Slot Monitoring** — Polls target platforms at configurable intervals (down to seconds) and reacts the moment a slot opens
- 📲 **Instant Telegram Alerts** — Sends booking confirmations, failure notices, and slot-found alerts directly to your Telegram bot or group
- 🔄 **Automatic Slot Booking** — Completes the full multi-step booking form autonomously, including personal data entry, document type selection, and confirmation
- 🛡️ **Proxy Rotation** — Supports HTTP/SOCKS5 proxy lists with automatic rotation and dead-proxy removal to avoid IP bans
- 🧠 **CAPTCHA Handling** — Integrated with third-party CAPTCHA-solving services (2Captcha, CapSolver) for seamless unblocking
- 🖥️ **Native Desktop GUI** — Sleek Eel + TailwindCSS + GSAP frontend packaged as a true desktop application (no browser required by the user)
- 🗂️ **Multi-Account Management** — Manage multiple applicant profiles, each with independent scheduling, proxy, and notification settings
- 🔑 **License Activation System** — Hardware-fingerprinted license keys with online activation and grace-period offline mode
- ⚙️ **Admin Panel** — Flask-powered web dashboard at `http://localhost:5000` for monitoring sessions, viewing logs, and managing accounts
- 🔁 **Auto-Update Engine** — Checks for new releases at startup and applies updates with a single click
- 💾 **SQLite Local Storage** — All profiles, logs, and session data stored locally; no cloud dependency
- 📋 **Detailed Activity Logs** — Timestamped, filterable logs for every monitoring session and booking attempt
- 🕐 **Scheduled Monitoring** — Set specific time windows to run the bot (e.g., monitor only 08:00–10:00 when slots typically drop)
- 🧩 **Modular Platform Adapters** — Each visa platform (VFS, BLS, TLS) is a self-contained plugin; new platforms can be added without touching core logic

---

## 🌍 Supported Platforms & Countries

| Platform | Full Name | Supported Countries (Examples) | Notes |
|---|---|---|---|
| **VFS Global** | VFS Global Services | 🇸🇦 Saudi Arabia, 🇦🇪 UAE, 🇪🇬 Egypt, 🇮🇳 India, 🇵🇰 Pakistan, 🇧🇩 Bangladesh | Schengen, UK, USA, Canada visas |
| **BLS International** | BLS International Services | 🇪🇬 Egypt, 🇲🇦 Morocco, 🇩🇿 Algeria, 🇹🇷 Turkey, 🇮🇳 India | Spain, Italy, Germany missions |
| **TLS Contact** | TLScontact Group | 🇲🇦 Morocco, 🇹🇳 Tunisia, 🇩🇿 Algeria, 🇸🇳 Senegal | France, UK, Switzerland visas |

> **Note:** Country and mission support is continuously expanded. Check the admin panel for the latest adapter versions.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Core Language** | Python 3.12 | Application logic, automation orchestration |
| **Browser Automation** | Playwright | Multi-browser slot detection and form filling |
| **Desktop GUI Framework** | Eel | Bridges Python backend to web-based frontend |
| **Frontend Styling** | TailwindCSS 3.x | Utility-first responsive UI styling |
| **Frontend Animation** | GSAP (GreenSock) | Smooth transitions, loading states, notifications |
| **Admin Dashboard** | Flask 3.x | Local web server for the management panel |
| **Database** | SQLite 3 | Local persistence for profiles, logs, licenses |
| **Notifications** | Telegram Bot API | Instant push alerts for slot availability and bookings |
| **Packaging** | PyInstaller | Single-file Windows/macOS executable |
| **Proxy Management** | Custom Proxy Rotator | HTTP/SOCKS5 rotation with health-checking |
| **CAPTCHA Solving** | 2Captcha / CapSolver | Automated CAPTCHA bypass integration |
| **Scheduler** | APScheduler | Cron-style session scheduling |

---

## 🚀 Installation

### Option A — End User (Installer)

The fastest way to get started. No Python required.

1. Download the latest installer from the [Releases](#) page:
   ```
   SmartBookingBot_Setup_v2.x.x.exe
   ```
2. Run the installer and follow the on-screen prompts.
3. Launch **Smart Appointment Booking Bot** from your desktop shortcut.
4. Enter your license key when prompted (see [Configuration](#-configuration)).

> **System Requirements:** Windows 10/11 (64-bit), 4 GB RAM minimum, internet connection.

---

### Option B — Developers (From Source)

#### Prerequisites

- Python 3.12+
- Git
- Node.js 18+ (for TailwindCSS build step)

#### Steps

```bash
# 1. Clone the repository
git clone https://github.com/your-org/smart-booking-bot.git
cd smart-booking-bot

# 2. Create and activate a virtual environment
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate

# 3. Install Python dependencies
pip install -r requirements.txt

# 4. Install Playwright browsers
playwright install chromium firefox webkit

# 5. Build the TailwindCSS bundle
npm install
npm run build:css

# 6. Initialize the local database
python scripts/init_db.py

# 7. Run the application
python main.py
```

---

## ⚙️ Configuration

### 1. License Activation

On first launch, you will be prompted for a license key.

```
License Key Format: SABB-XXXX-XXXX-XXXX-XXXX
```

- Enter your key in the **Activation** screen.
- The key is bound to your machine's hardware fingerprint.
- Internet connection is required for initial activation; subsequent launches allow a **7-day offline grace period**.

To transfer your license to a new machine, deactivate it first via **Settings → License → Deactivate**.

---

### 2. Telegram Bot Setup

To receive booking alerts and confirmations on Telegram:

1. Open Telegram and search for **@BotFather**.
2. Send `/newbot` and follow the prompts to create your bot.
3. Copy the **Bot Token** provided by BotFather.
4. Start a conversation with your new bot (or add it to a group).
5. Retrieve your **Chat ID** using `https://api.telegram.org/bot<TOKEN>/getUpdates`.
6. In the application, navigate to **Settings → Notifications** and fill in:

```ini
TELEGRAM_BOT_TOKEN = 123456789:AABBCCDDEEFFaabbccddeeff-xxxxxxxx
TELEGRAM_CHAT_ID   = -1001234567890
```

Test the connection using the **Send Test Message** button.

---

### 3. Proxy Configuration

Navigate to **Settings → Proxies** to manage your proxy pool.

Proxies can be entered manually or imported from a `.txt` file (one proxy per line):

```
# Supported formats:
http://user:pass@host:port
socks5://user:pass@host:port
http://host:port
```

**Proxy Settings:**

| Setting | Description | Default |
|---|---|---|
| Rotation Mode | `sequential` or `random` | `random` |
| Health Check Interval | Seconds between proxy tests | `60` |
| Max Failures | Remove proxy after N failures | `3` |
| Timeout | Per-request proxy timeout (s) | `15` |

---

### 4. Platform Configuration

Each visa platform adapter is configured independently:

```json
{
  "platform": "VFS",
  "country": "Egypt",
  "mission": "Germany",
  "visa_category": "Schengen",
  "applicant_profiles": ["profile_001", "profile_002"],
  "check_interval_seconds": 30,
  "run_window": { "start": "08:00", "end": "12:00" },
  "max_retries": 5
}
```

---

## ▶️ Usage — Quick Start

1. **Launch** the application (desktop shortcut or `python main.py`).
2. **Activate** your license key on first run.
3. Go to **Profiles → Add New** and fill in your applicant details (name, passport number, visa category, etc.).
4. Go to **Platforms** and select your target (e.g., VFS Egypt → Germany Mission).
5. (Optional) Add proxies under **Settings → Proxies**.
6. Configure your Telegram bot under **Settings → Notifications**.
7. Click **▶ Start Monitoring**.

The bot will begin polling the selected platform. When a slot is found:
- 🟢 The UI flashes a green alert with slot details.
- 📲 A Telegram notification is sent immediately.
- 🤖 The bot proceeds to auto-book using your applicant profile.
- ✅ A booking confirmation (with reference number) is sent via Telegram.

To stop monitoring at any time, click **⏹ Stop**.

---

## 🖥️ Admin Panel

The Flask-powered admin panel provides a real-time overview of all bot activity.

**Access:** Open your browser and navigate to:
```
http://localhost:5000
```

**Default Credentials:**

| Field | Value |
|---|---|
| Username | `admin` |
| Password | `admin123` |

> ⚠️ **Change the default password immediately** after first login via **Admin → Settings → Change Password**.

**Admin Panel Features:**

- 📊 **Dashboard** — Live session status, slots found counter, bookings made, uptime
- 👥 **Account Manager** — Create, edit, and delete applicant profiles
- 📜 **Activity Logs** — Full timestamped log viewer with search and export (CSV/JSON)
- 🔑 **License Info** — View activation status, expiry date, and machine fingerprint
- 🔌 **Platform Adapters** — Enable/disable adapters, view adapter version and last update
- 🔔 **Notification Tester** — Send a test Telegram message
- 🔄 **Update Manager** — Check for and apply application updates

---

## 📁 Project Structure

```
smart-booking-bot/
│
├── main.py                  # Application entry point
├── requirements.txt         # Python dependencies
├── package.json             # Node.js dependencies (TailwindCSS)
│
├── core/
│   ├── monitor.py           # Slot monitoring engine
│   ├── booker.py            # Automated booking logic
│   ├── scheduler.py         # APScheduler session management
│   ├── proxy_manager.py     # Proxy pool rotation & health checks
│   ├── captcha.py           # CAPTCHA solving integrations
│   ├── notifier.py          # Telegram notification dispatcher
│   └── license.py           # License activation & validation
│
├── platforms/
│   ├── base_adapter.py      # Abstract base class for platform adapters
│   ├── vfs/
│   │   └── adapter.py       # VFS Global adapter
│   ├── bls/
│   │   └── adapter.py       # BLS International adapter
│   └── tls/
│       └── adapter.py       # TLS Contact adapter
│
├── admin/
│   ├── app.py               # Flask admin panel application
│   ├── routes/              # Admin panel route handlers
│   └── templates/           # Jinja2 HTML templates
│
├── web/
│   ├── index.html           # Main Eel frontend entry point
│   ├── css/
│   │   └── output.css       # Compiled TailwindCSS
│   ├── js/
│   │   ├── app.js           # Main frontend logic
│   │   └── animations.js    # GSAP animation definitions
│   └── components/          # Reusable UI components
│
├── database/
│   ├── schema.sql           # SQLite schema definitions
│   └── db.py                # Database connection & query helpers
│
├── scripts/
│   ├── init_db.py           # Database initializer
│   └── build.spec           # PyInstaller build specification
│
├── assets/
│   ├── icons/               # Application icons
│   └── screenshots/         # UI screenshots
│
├── logs/                    # Runtime log files (auto-created)
├── config.json              # User configuration (auto-created)
└── README.md
```

---

## 🏗️ Building from Source

The application is packaged using **PyInstaller** into a single executable.

### Build Steps

```bash
# 1. Ensure you are in the project root with venv activated

# 2. Build the TailwindCSS production bundle
npm run build:css:prod

# 3. Run PyInstaller with the provided spec file
pyinstaller scripts/build.spec

# The output will be at:
# dist/SmartBookingBot/SmartBookingBot.exe   (folder mode)
# dist/SmartBookingBot.exe                   (one-file mode)
```

### `build.spec` Key Settings

```python
# scripts/build.spec (excerpt)
a = Analysis(
    ['main.py'],
    datas=[
        ('web', 'web'),
        ('admin/templates', 'admin/templates'),
        ('platforms', 'platforms'),
        ('database/schema.sql', 'database'),
        ('assets', 'assets'),
    ],
    hiddenimports=[
        'eel', 'playwright', 'flask', 'apscheduler',
        'telegram', 'sqlite3',
    ],
)

exe = EXE(
    pyz, a.scripts,
    name='SmartBookingBot',
    icon='assets/icons/app.ico',
    onefile=True,
    console=False,
)
```

### Creating the Windows Installer

Use [NSIS](https://nsis.sourceforge.io/) or [Inno Setup](https://jrsoftware.org/isinfo.php) with the provided script:

```bash
# With Inno Setup installed:
iscc scripts/installer.iss

# Output: dist/SmartBookingBot_Setup_v2.x.x.exe
```

---

## 🔧 Troubleshooting

### ❌ License Activation Fails

- Ensure you have an active internet connection during activation.
- Check that your system clock is accurate (time drift can cause validation failures).
- If you've recently changed hardware, contact support to reset your license.

---

### ❌ Browser Fails to Launch / Playwright Error

```bash
# Reinstall Playwright browsers
playwright install --with-deps chromium firefox webkit
```

- On Windows, ensure Microsoft Visual C++ Redistributable is installed.
- Check that no antivirus is blocking Playwright's browser binaries.

---

### ❌ Platform Login Fails (VFS / BLS / TLS)

- Verify your applicant credentials are correct in **Profiles**.
- The target platform may have updated its login flow; check for a bot update via the Admin Panel.
- Try disabling proxies temporarily to rule out IP blocking.
- Enable **Stealth Mode** under platform settings to reduce bot detection.

---

### ❌ Telegram Notifications Not Received

- Confirm the bot token and chat ID are correct in **Settings → Notifications**.
- Make sure you have sent at least one message to the bot before the bot can message you.
- Use the **Send Test Message** button to verify connectivity.

---

### ❌ Admin Panel Not Loading

- Ensure port `5000` is not blocked by your firewall.
- Check that no other application is using port 5000.
- Restart the application; the Flask server starts automatically with the app.

---

### ❌ High CPU / Memory Usage

- Reduce the number of simultaneous monitoring sessions.
- Increase the `check_interval_seconds` value for less critical platforms.
- Ensure unused Playwright browser instances are properly closed between sessions.

---

### 📋 Log Files

Logs are stored at:
```
Windows:  %APPDATA%\SmartBookingBot\logs\
macOS:    ~/Library/Application Support/SmartBookingBot/logs/
```

Share the latest `.log` file when contacting support.

---

## 📸 Screenshots

| Main Dashboard | Slot Alert | Admin Panel |
|---|---|---|
| ![Dashboard](assets/screenshots/dashboard.png) | ![Alert](assets/screenshots/slot-alert.png) | ![Admin](assets/screenshots/admin-panel.png) |

| Profile Manager | Proxy Settings | Telegram Notification |
|---|---|---|
| ![Profiles](assets/screenshots/profiles.png) | ![Proxies](assets/screenshots/proxies.png) | ![Telegram](assets/screenshots/telegram-alert.png) |

> 📌 *Screenshots reflect v2.x UI. Actual appearance may vary by version.*

---

## 🤝 Support & Links

For licensing inquiries, bug reports, or feature requests — reach out through any of the channels below:

<p>
  <a href="https://www.linkedin.com/in/onlineunknown/" target="_blank">🔗 <strong>LinkedIn</strong> — Connect professionally</a><br/>
  <a href="https://buymeacoffee.com/onlineunknowns" target="_blank">☕ <strong>Buy Me a Coffee</strong> — Support development</a><br/>
  <a href="https://wa.me/201286016083" target="_blank">💬 <strong>WhatsApp</strong> — Direct support chat</a>
</p>

> Response time: typically within 24 hours on business days.

---

## 📄 License

**Smart Appointment Booking Bot** is **proprietary software**.

```
Copyright © 2024–2026. All rights reserved.

This software and its source code are the exclusive property of the author.
Unauthorized copying, modification, distribution, sublicensing, or reverse
engineering of this software, in whole or in part, via any medium, is
strictly prohibited without the express written permission of the author.

Use of this software is governed by the End-User License Agreement (EULA)
provided at the time of purchase. A valid, activated license key is required
for operation.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. THE AUTHOR
SHALL NOT BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY ARISING FROM
THE USE OF THIS SOFTWARE.
```

---

<p align="center">
  Made with ❤️ by <a href="https://www.linkedin.com/in/onlineunknown/" target="_blank">@onlineunknown</a>
  &nbsp;•&nbsp;
  <a href="https://buymeacoffee.com/onlineunknowns" target="_blank">☕ Support the project</a>
  &nbsp;•&nbsp;
  <a href="https://wa.me/201286016083" target="_blank">💬 Get in touch</a>
</p>
