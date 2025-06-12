# 🕌 Azan Notifications v1.0 – Home Assistant Blueprint

**By [Shady Nafie — Smart Tech Arabic](https://smarttecharabic.com)**

A fully customisable **Home Assistant** automation blueprint that sends high-priority notifications for all five daily Islamic prayers. Designed for modern Muslim smart homes, this solution includes bilingual messages, platform-aware features, and an optional test mode.

---

## ✨ Features

- 🔔 Smart notifications for **Fajr, Dhuhr, Asr, Maghrib, and Isha**
- 🌐 Bilingual messages (Arabic and English) – **fully editable**
- 🎨 Custom icons and colours per prayer
- ⚙️ Test mode included to verify setup
- 📱 Compatible with both Android and iOS
- ✅ Interactive action buttons (Android only):
  - *Mark as Prayed*
  - *Snooze for 5 minutes*

---

## 📋 Prerequisites

Make sure the following are in place before using this blueprint:

1. **Islamic Prayer Times** integration is installed and correctly configured
2. Each prayer time is available as a `sensor` with `device_class: timestamp`
3. You have the **Home Assistant Mobile App** installed and notifications enabled
4. Your mobile device is selected under `notify_device`

---

## 🛠️ Setup Instructions

1. Download or paste the YAML into your `blueprints/automation` folder
2. In Home Assistant, go to **Automations → Blueprints**, then **Import Blueprint**
3. Select **Azan Notifications v1.0**
4. Configure:
   - Your mobile device
   - Sensors for each prayer
   - Optional custom messages
   - Enable/disable prayers as needed

---

## 🧪 Test Mode

You can test the system by assigning a custom test `timestamp` sensor and enabling **Test Notification**. This is useful to validate the configuration without waiting for actual prayer times.

---

## 📷 Screenshots

> _(Optional: Add screenshots of notifications on mobile devices if desired)_

---

## 📌 Notes

- Only Android supports interactive actions like *Mark as Prayed* or *Snooze*
- iOS users will still receive styled, persistent prayer alerts

---

## 🤝 Contributing

This blueprint is open for feedback and improvements. Please raise an issue or submit a pull request.

---

## 📜 License

MIT License © 2025 [Shady Nafie](https://smarttecharabic.com)
