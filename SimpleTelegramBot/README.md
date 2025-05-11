# 🤖 Simple Telegram Bot  
**Multifunctional. Secure. Expandable.**

A powerful and flexible Telegram bot designed for remote interaction with your Android device using [MacroDroid](https://www.macrodroid.com/). Whether you need a basic tracker, notification forwarder, or a full-featured remote control panel — this setup is for you.

📲 **[Link to Macro](https://www.macrodroidlink.com/macrostore?id=25355)**

---

## 🔐 Key Features

- **User ID-based Authorization** — Only your Telegram ID can control the bot  
- **Security Shutdown** — Auto-deactivates on command from unauthorized users  
- **Custom Command Support** — Add your own actions via macro editing  
- **Device Info Retrieval** — Battery, RAM, model, and more  
- **Real-time Geolocation** — GPS-based location reporting  
- **Find My Phone Tools** — Activate sound and flash remotely  
- **Notification Forwarding** — Get SMS, call, and app alerts *(requires extra triggers)*  
- **Call Handling** — Reject or initiate calls remotely  
- **Intruder Detection** — Takes a photo if the wrong PIN is entered  
- **Multilingual Support** — Switch interface languages using translated strings  
- **File Capture & Storage** — Auto-save photos, videos, documents, audio  
- **Note Saving** — Save messages to local file notes  
- **VirusTotal URL Checker** — Scan links for safety *(API key required)*  
- **DeepSeek AI Chat** — Integrated chat assistant *(API key required)*  
- ...and more!

---

## 🛠️ Setup Instructions

1. Open Telegram and search for `@BotFather`
2. Send the command: `/newbot`
3. Follow prompts: name your bot and choose a username
4. Copy the API Token sent by BotFather
5. Paste it into the `apiToken` variable in your MacroDroid macro
6. Enable the macro and run the “Test Macro” to register your Webhook  
✅ Your bot is now ready to use!

---

## 💬 Default Commands

| Command                        | Description                                                                |
|--------------------------------|----------------------------------------------------------------------------|
| `/start`                       | Activate the bot and check user access                                     |
| `/help`                        | Show all available commands and instructions                               |
| `/device_info`                 | Show device info                                                           |
| `/geo_position`                | Show GPS location                                                          |
| `/sound_search`                | Play a loud sound to find your phone                                       |
| `/reject_call`                 | Reject incoming call                                                       |
| `/call_to +1234567890`         | Call a number remotely                                                     |
| `/note text`                   | Save a text note                                                           |
| `/check_url https://...`       | Check a link with VirusTotal *(API key required)*                          |
| `Sent files`                   | Store received images, audio, video, and documents                         |
| `Any message`                  | Chat with AI assistant *(DeepSeek, API key required)*                      |
| `/deepseek_clear`              | Clear DeepSeek chat history                                                |

⚠️ Commands may vary slightly depending on your macro version.

⚠️ These commands are examples. You can fully modify or extend them for your use case. Current commands are functional out-of-the-box.

---

## 🌍 Language Support

The bot supports multilingual output using translation dictionaries.  
You can easily switch the interface language (e.g., English, Russian, Spanish) to improve user experience.

---

## 💡 Notes

- Requires proper device permissions (location, camera, etc.)
- Fully customizable via MacroDroid
- VirusTotal API key needed for link scanning  
  ➤ [Get API Key](https://www.virustotal.com)
- DeepSeek AI requires key  
  ➤ [Get API Key](https://openrouter.ai/deepseek/deepseek-chat-v3-0324:free)

---

## ⚠️ Stability Requirements

The bot uses Webhook — for stable operation:

- The device **must be online**
- MacroDroid **must be allowed to run in the background**
- **Disable battery optimizations** and auto-kill policies for MacroDroid

---

## 🙏 Special Thanks

This project wouldn’t exist without the help and feedback from the amazing contributors:

- **@vavlut** — For testing, finding bugs and helping to fix them

---

## 🧩 Use Cases

Build your own:

- Anti-theft tracker  
- Remote control panel  
- SMS/call forwarder  
- AI chatbot via Telegram  
- Macro automation gateway

---

📲 **[Link to Macro](https://www.macrodroidlink.com/macrostore?id=25355)**

---

<details>
<summary>📝 Macro Changelog</summary>

### 2025-05-10
- ✅ Fixed: web registration conditions  
- ✅ Fixed: chatId condition bug

### 2025-05-06
- ➕ Added: DeepSeek chat via openrouter.ai (requires token)  
- 🔔 Added: notification after saving file

### 2025-05-05
- ➕ Added: `/check_url` with VirusTotal  
- 🛠️ Fixed: webhook registration issue  
- 🛠️ Fixed: empty VirusTotal results  
- 🔁 Updated: random `webhookId` generation  
- ➕ Added: regex for value checks

### 2025-05-04
- ➕ Added: FileSave block

### 2025-04-27
- ➕ Added: `/note` command

### 2025-04-18
- ➕ Added: Callback handler for call actions

### 2025-04-16
- ➕ Added: Language dictionaries  
- ➕ Added: `/reject_call`, `/call_to` commands

### 2025-04-10
- ➕ Added: incoming call notifications  
- ➕ Added: SMS forwarding

### 2025-04-09
- ➕ Initial release  
- Commands: `/start`, `/help`, `/device_info`, `/geo_position`, `/sound_search`
</details>
