# 🤝 ShakeContacts

[![Readme EN](https://img.shields.io/badge/README-EN-blue.svg)](./README.md)
[![Readme RU](https://img.shields.io/badge/README-RU-blue.svg)](./README_RU.md)
[![GitHub license](https://img.shields.io/badge/license-MIT-458a7b.svg)](../LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-BespredeL%2FMacroDroid-181717?logo=github&logoColor=white)](https://github.com/BespredeL/MacroDroid)
[![MacroDroid](https://img.shields.io/badge/MacroDroid-Template%20Store-orange.svg)](https://templates.macrodroid.com/user/94)

🤝 Quickly share contact information using QR codes with MacroDroid.

Shake the device to open a contact selection menu, choose the information you want to share, and display the corresponding QR code.

📲 **[Macro Link](https://templates.macrodroid.com/view/31634)** | 👤 **[All macros by BespredeL](https://templates.macrodroid.com/user/94)**

---

## 🚀 Features

- 🤳 Launch by shaking the device
- 🏠 Works only when the launcher/home screen is in the foreground
- 📇 Contact information setup menu
- ☎️ Share phone contact as a vCard QR code
- 🌐 Share website and social profiles
- 💬 Share WhatsApp
- ✈️ Share Telegram
- 🔗 Support for multiple social networks and services
- 📱 Display generated QR codes directly on the device
- 💾 Save QR codes locally
- 🌍 Automatic language detection
- 🔐 Works locally without an Internet connection after setup

### 🌐 Supported Services

- ☎️ Phone
- 🌐 Website
- 💬 WhatsApp
- ✈️ Telegram
- 👤 Facebook
- 📸 Instagram
- 💼 LinkedIn
- 🐙 GitHub
- 🦊 GitLab
- 🎨 Behance
- 🏀 Dribbble
- 🎮 Discord
- 👻 Snapchat
- 🔒 Signal
- 🎵 TikTok
- ▶️ YouTube
- 🟦 VK
- 🟠 OK
- 🐦 X
- 📌 Pinterest
- 👽 Reddit
- 🧵 Threads
- 🎮 Twitch
- 📱 Viber

---

## ⚙️ How It Works

The macro uses the MacroDroid **Shake Device** trigger and custom scenes.

1. 🤳 Shake the device while the home screen is active.
2. 📋 Select the contact information you want to display.
3. 📱 MacroDroid opens a full-screen QR code view.
4. 🔍 Scan the QR code with another device.
5. 💾 Generated QR codes are stored locally for quick access.

For phone contacts, the macro creates a `vCard 3.0` QR code containing the configured name, phone number, email, organization and job title.

---

## 🧩 Requirements

- 📱 Android device
- 📲 MacroDroid installed
- 🤳 Device with a working accelerometer/motion sensor
- 💾 Storage access for saving QR codes
- 🔐 Required MacroDroid permissions for file access and custom scenes

---

## 🔧 Configuration

The first run opens the contact configuration interface.

### 📌 Contact Information

| Field                   | Description                                                           |
|-------------------------|-----------------------------------------------------------------------|
| `phone`                 | Phone number and vCard contact details                                |
| `fullname`              | Contact name                                                          |
| `email`                 | Email address                                                         |
| `organization_name`     | Organization/company name                                             |
| `organization_position` | Job title                                                             |
| `website`               | Website username or address                                           |
| Social services         | Username, phone number or profile identifier depending on the service |

Each service has its own `active` flag and value. Only enabled services are shown in the selection menu.

### 📌 Storage

| Variable     | Description                        | Default               |
|--------------|------------------------------------|-----------------------|
| `rootPathQR` | Root path used for QR-code storage | `/sdcard/MacroDroid/` |
| `dirQR`      | QR-code storage folder             | `ShakeContacts`       |

QR codes are stored as PNG files in:

`/sdcard/MacroDroid/ShakeContacts/`

A `.nomedia` file is also created in the folder so the QR-code images are not added to the media gallery.

---

## 🌐 Usage

### 🤳 Open the menu

Shake the device while the Android launcher/home screen is in the foreground.

The macro displays a list of enabled contact services.

### 📱 Display a QR code

Tap a service from the list.

The macro displays:

- QR code image
- The encoded contact value
- An `OK` button to close the view

### ⚙️ Change contact settings

Open the settings option from the contact selection scene and update the desired contact information or enabled services.

---

## 💡 Use Cases

- 📱 Quickly share a phone number without typing
- 🌐 Share a website or social profile
- 💬 Share WhatsApp or Telegram contact information
- 🤝 Exchange contact details between phones
- 🖥️ Display a profile on a phone screen for scanning
- 📇 Share a complete contact card as a QR code

---

## 🌍 Languages

The macro automatically detects the device language and uses the corresponding interface translations when available.

English is used as the fallback language.

---

## 🔐 Privacy

- 📱 Contact data is processed locally by MacroDroid.
- 💾 QR codes are saved locally on the device.
- 🌐 No Internet connection is required after setup.
- 📤 The macro does not upload contact data to a remote server.

---

## ⚠️ Limitations

- QR-code scanning behavior depends on the scanner/application used on the receiving device.
- Shake detection depends on the device's motion sensor and Android behavior.
- The macro is designed to activate from the Android launcher/home screen.
- Storage permissions may be required depending on the Android version.
- QR codes are generated and stored as PNG files on the device.
