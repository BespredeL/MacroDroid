# 📱 MacroDroid Macros Collection

[![Readme EN](https://img.shields.io/badge/README-EN-blue.svg)](https://github.com/BespredeL/MacroDroid/blob/main/README.md)
[![Readme RU](https://img.shields.io/badge/README-RU-blue.svg)](https://github.com/BespredeL/MacroDroid/blob/main/README_RU.md)
[![GitHub license](https://img.shields.io/badge/license-MIT-458a7b.svg)](https://github.com/BespredeL/MacroDroid/blob/main/LICENSE)

A curated collection of powerful and customizable [MacroDroid](https://www.macrodroid.com) macros to automate your Android device.

Each macro is stored in its own folder with:

- The macro file (for direct import)
- A dedicated `README.md` with full instructions, features, and changelog

---

## 📦 Macro List

### 🤖 [Simple Telegram Bot](./SimpleTelegramBot/)

Remote control your Android device via Telegram.

- 🔐 Authorized control via Telegram ID
- 📍 Geolocation, device info, and sound alert tools
- 🔁 Notification and SMS forwarding
- 📸 Intruder detection with photo capture
- 📞 Call handling (reject/call specific number)
- 🧠 AI assistant via DeepSeek (optional)
- 🌐 URL scanning via VirusTotal (optional)
- 🗂️ Save media, documents, and text notes
- 🌍 Multilingual interface support

📄 **[Detailed Description →](./SimpleTelegramBot/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=25355)**

---

### 🔦 [Shake Flashlight](./ShakeFlashlight/)

Turn on your flashlight by simply shaking your phone in low-light conditions.

- 🌑 Activates only if ambient light < 50 lux
- 🔒 Works only when screen is locked but turned on
- 📏 Requires proximity sensor to be clear
- ⚙️ Fully configurable shake sensitivity

📄 **[Detailed Description →](./ShakeFlashlight/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=134)**

---

### 🛡️ [Parental Control](./ParentalControl/)

This macro is designed for parental monitoring - it collects the following data from a child’s device and sends it securely to the parent’s device:

- 📞 Incoming & outgoing calls
- ✉️ SMS messages
- 🔔 Notifications from apps
- 📍 GPS location tracking
- 📶 Wi-Fi connection history
- 🌍 Multi-language support via `langs` variable

📄 **[Detailed Description →](./ParentalControl/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=27550)**

---

### 💡 [Wake PC](./WakePC/)

This macro allows you to turn on a computer or any other device in your local network using Wake-on-LAN (WoL).
Simply connect to the same Wi-Fi network, enter the device’s MAC address and broadcast address - and MacroDroid will send a special *Magic Packet*
that powers it on.

- 🖥️ Automatic/manual WOL packet sending
- 🌐 Broadcast support with auto-detection
- 📡 Ability to wake the device from other macros or widgets
- 🔧 Customizable MAC address and network segment settings

📄 **[Detailed Description →](./WakePC/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=27708)**

---

### 📸 [IntruderCam](./IntruderCam/)

This macro automatically records any unauthorized access attempt and collects key evidence.

- 🤳 Takes photos from the front and rear cameras in case of unsuccessful login attempts (by default, 2 attempts within 10 minutes).
- 🗺️ Saves GPS coordinates as an HTML page with an interactive map.
- 🎥 Records 30 seconds of video from the front camera.
- 🔔 After successful unlocking, it shows a violation notification.

📄 **[Detailed Description →](./IntruderCam/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=27640)**

---

### 🛡️ [Anti-Scam Protector](./AntiScamProtector/)

Protects against phone call scams that use simultaneous SMS with confirmation codes.

- 📴 Hides incoming code notifications during calls
- 📩 Sends emergency alert SMS to trusted contact
- 🚨 Shows fraud warning notifications and dialogs
- ⏱️ Automatically ends calls if no response in 30 sec
- 🔄 Reinforces warning with repeated dialog
- 🌍 Multi-language support via `langs` variable

📄 **[Detailed Description →](./AntiScamProtector/README.md)**

📲 **[Macro Link](https://www.macrodroidlink.com/macrostore?id=25801)**

---

> ℹ️ More macros coming soon - stay tuned for updates.

---

## 🛠 Usage Instructions

1. Open MacroDroid on your Android device
2. Import the macro from the `.macro` file inside the folder
3. Read the `README.md` in each folder for detailed setup
4. Customize logic, triggers, and variables as needed

---

## 💬 Feedback & Contributions

Have suggestions, found a bug, or created your own version?
Feel free to open issues or submit a pull request.

---

## 🧩 About This Repository

This repository is intended as a toolbox of advanced MacroDroid automation templates.
It’s perfect for:

- 🔐 Security and anti-theft automation
- 📦 Remote device management
- 🧠 AI assistant and automation workflows
- 📡 Notification forwarding setups
- 🔧 Learning and building your own complex macros

---

📣 **Questions? Ideas?**
Feel free to start a discussion or contact via Email [hello@bespredel.name](mailto:hello@bespredel.name).

---