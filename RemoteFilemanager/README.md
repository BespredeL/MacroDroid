# 📁 Remote Filemanager

🤖 A web-based file manager for Android powered by MacroDroid HTTP Server.

Access and manage your device files directly from a browser - fully local, no cloud required.

---

## 🚀 Features

- 🌐 Browser-based file access
- 📂 Directory navigation
- 📄 File listing
- 📊 File info (size, date)
- 🗑️ Delete files and folders
- 📁 Create directories
- 📋 Copy files
- ✂️ Move files
- 🌍 Multi-language support
- 🔐 Works over local network (Wi-Fi / hotspot)

### ⚠️ In Progress

- 📥 File upload
- 📤 File sharing

---

## ⚙️ How It Works

This macro uses MacroDroid's built-in HTTP Server to turn your device into a local file server.

Open a browser → enter device address → manage files.

---

## ⚡ Installation

1. Download macro file:
   Remote_Filemanager.macro

2. Import into MacroDroid:
   Menu → Import/Export → Import Macro

3. Enable the macro

---

## 🔧 Configuration

### 📌 Main Variables

| Variable       | Description             | Example     |
|----------------|-------------------------|-------------|
| port           | HTTP server port        | 8080        |
| rootPath       | Root directory          | /sdcard/    |
| allowedFileExt | Allowed file extensions | jpg,png,txt |
| currentLang    | UI language             | en, ru      |

---

### 🔐 Security

| Setting      | Description                      |
|--------------|----------------------------------|
| IP whitelist | Restrict access by IP (optional) |

---

## 🌐 Usage

After starting the macro:

1. Get your device IP (e.g. 192.168.1.100)
2. Open in browser:
http://<device_ip>:\<port>/rfm

Example:
http://192.168.1.100:8080/rfm

---

## 💡 Use Cases

- Transfer files between phone and PC
- Access logs or app data
- Wireless file management
- Turn your phone into a mini NAS

---

## ⚠️ Limitations

- Performance depends on device
- No HTTPS (local network only)
- Limited by MacroDroid capabilities