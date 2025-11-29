# 🤖 Simple Telegram Bot

[![Readme EN](https://img.shields.io/badge/README-EN-blue.svg)](./README.md)
[![Readme RU](https://img.shields.io/badge/README-RU-blue.svg)](./README_RU.md)
[![GitHub license](https://img.shields.io/badge/license-MIT-458a7b.svg)](../LICENSE)

**Multifunctional. Secure. Expandable.**

A powerful and flexible Telegram bot designed for remote interaction with your Android device using [MacroDroid](https://www.macrodroid.com/). Whether you need a basic tracker, notification forwarder, or a full-featured remote control panel - this setup is for you.

📲 **[Link to Macro](https://www.macrodroidlink.com/macrostore?id=25355)**

---

## 🔐 Key Features

- **User ID-based Authorization**  
- **Security Shutdown on Unauthorized Access**  
- **Custom Commands Support**  
- **Device Info & Status**  
- **GPS Geolocation Retrieval**  
- **Find My Phone Sound & Flash**  
- **SMS & Notification Forwarding**  
- **Call Reject / Dial**  
- **Intruder Detection (Camera Trigger)**  
- **Multilingual Interface**  
- **Auto Save Media & Files**  
- **Text Note Saving**  
- **VirusTotal URL Scan** *(API key)*  
- **DeepSeek AI Chat Assistant** *(API key)*

---

## 🛠️ Setup Instructions

1. Open Telegram and search for `@BotFather`  
2. Send `/newbot`  
3. Follow the prompts to name and create your bot  
4. Copy the API Token from BotFather  
5. Paste into `apiToken` in your macro  
6. Enable macro and run "Test Macro"  
✅ Done!

---

## 💬 Default Commands

| Command | Description |
|--------|-------------|
| `/start` | Activate and verify access |
| `/help` | Show available commands |
| `/device_info` | Show phone stats |
| `/geo_position` | Show location |
| `/sound_search` | Find phone by sound |
| `/reject_call` | Reject incoming call |
| `/call_to +1234567890` | Dial number |
| `/note text` | Save note |
| `/check_url https://...` | Check URL *(VirusTotal)* |
| `/deepseek_clear` | Clear AI chat |
| Any text | AI response *(DeepSeek)* |

---

## 🌍 Language Support

Switch interface languages dynamically. Dictionaries included: English, Russian.

---

## ⚙️ Notes

- Give all necessary permissions (camera, location, etc.)
- Disable battery optimizations for MacroDroid
- By default, some functionality is disabled. To enable, activate the necessary triggers
- [VirusTotal API Key](https://www.virustotal.com)  
- [DeepSeek Token](https://openrouter.ai/deepseek/deepseek-chat-v3-0324:free)

---

## 🧩 Use Cases

- Anti-theft tracker  
- Remote control  
- Call/SMS alerts  
- AI assistant in Telegram  
- Custom macro hub

---

## 🙏 Special Thanks

- **@vavlut** - testing & QA