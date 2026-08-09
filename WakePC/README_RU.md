# 💡 Включение ПК

[![Readme EN](https://img.shields.io/badge/README-EN-blue.svg)](./README.md)
[![Readme RU](https://img.shields.io/badge/README-RU-blue.svg)](./README_RU.md)
[![GitHub license](https://img.shields.io/badge/license-MIT-458a7b.svg)](../LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-BespredeL%2FMacroDroid-181717?logo=github&logoColor=white)](https://github.com/BespredeL/MacroDroid)

**Включение компьютера по сети (WoL)**

Этот макрос позволяет включить компьютер или другое устройство в локальной сети с помощью технологии Wake-on-LAN (WoL).
Достаточно подключиться к той же Wi-Fi сети, указать MAC-адрес и broadcast-адрес устройства - и MacroDroid отправит специальный *Magic Packet*,
который запустит устройство.

📲 **[Ссылка на макрос](https://templates.macrodroid.com/view/27708)** | 👤 **[Все макросы BespredeL](https://templates.macrodroid.com/user/94)**

---

## ⚙️ Как работает

- Отправляет UDP-пакет формата Wake-on-LAN;
- Работает при условии, что компьютер поддерживает и настроен на приём WoL-сигналов;
- Может запускаться вручную, по расписанию или при подключении к домашней сети.

---

## 🔧 Требования

- ПК или устройство должно быть подключено по **Ethernet**;
- В **BIOS/UEFI** необходимо включить опцию *Wake on LAN*;
- Телефон должен быть подключён к той же **Wi-Fi сети**, что и устройство.

---

## 💬 Совет

Можно изменить триггер - например, включать компьютер автоматически при подключении к Wi-Fi дома или по голосовой команде.