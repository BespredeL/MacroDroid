# 🎚️ Fast Media Vol.

[![Readme EN](https://img.shields.io/badge/README-EN-blue.svg)](./README.md)
[![Readme RU](https://img.shields.io/badge/README-RU-blue.svg)](./README_RU.md)
[![GitHub license](https://img.shields.io/badge/license-MIT-458a7b.svg)](../LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-BespredeL%2FMacroDroid-181717?logo=github&logoColor=white)](https://github.com/BespredeL/MacroDroid)

🔊 Fast media volume toggle for Android using MacroDroid hardware volume buttons.

Mute media instantly with a long press of Volume Down and restore the previously saved volume with a long press of Volume Up.

📲 **[Macro Link](https://templates.macrodroid.com/view/31466)** | 👤 **[All macros by BespredeL](https://templates.macrodroid.com/user/94)**

---

## 🚀 Features

- 🔇 Mute media with a long press of Volume Down
- 🔊 Restore the previous media volume with a long press of Volume Up
- 💾 Automatically saves the current media volume before muting
- 📢 Displays the current status after each action
- ⚡ Quick hardware button control
- 🌍 Multi-language status messages
- 🪶 Lightweight and battery-friendly

---

## ⚙️ How It Works

The macro uses MacroDroid's volume button triggers and media volume control.

1. 🔇 Hold the **Volume Down** button to mute media. The current media volume is saved automatically.
2. 🔊 Hold the **Volume Up** button to restore the previously saved volume.
3. 📢 A short status message shows whether media sound was turned off or turned on.

The volume button triggers are configured so the normal volume change caused by the long press is not applied.

---

## 🧩 Requirements

- 📱 Android device
- 📲 MacroDroid installed
- 🔘 Physical volume buttons
- 🔐 Required MacroDroid permissions for volume button triggers

---

## 🔧 Configuration

The macro does not require manual configuration.

### 📌 Internal Variables

| Variable      | Description                                      | Example    |
|---------------|--------------------------------------------------|------------|
| `level`       | Saved media volume level before muting           | `0-100`    |
| `currentLang` | Current language used for status messages        | `en`, `ru` |
| `langs`       | Dictionary containing translated status messages | `en`, `ru` |

The previous volume is saved automatically during each mute operation.

---

## 🌐 Usage

### 🔇 Mute media

Hold the **Volume Down** button.

The macro:

1. Saves the current media volume.
2. Sets media volume to `0`.
3. Displays a message indicating that media sound is turned off.

### 🔊 Restore media volume

Hold the **Volume Up** button.

The macro:

1. Reads the previously saved volume.
2. Restores the media volume.
3. Displays a message indicating that media sound is turned on.

---

## 💡 Use Cases

- 🔇 Quickly mute music or videos
- 🔊 Restore the previous media volume with one hardware button action
- 🎧 Convenient volume control while using headphones
- 📱 Control media sound without opening the volume panel

---

## 🌍 Languages

The macro includes status messages in:

- 🇬🇧 English
- 🇷🇺 Russian

The language is selected automatically from the device language code.

---

## ⚠️ Limitations

- The macro controls **media volume**, not ringtone or notification volume.
- It relies on MacroDroid's volume button trigger and Android's hardware volume buttons.
- The saved volume is stored in a local macro variable.
- The **Music Active** constraint is included in the macro but currently disabled.
- Behavior may depend on Android and device-specific restrictions for volume button monitoring.
