# 🕌 Azan Notifications v1.0 – Home Assistant Blueprint

**By [Shady Nafie — Smart Tech Arabic](https://smarttecharabic.com)**

A customisable **Home Assistant** automation blueprint that delivers timely notifications for the five daily Islamic prayers. It supports bilingual messages and works across both Android and iOS devices.

---

## ✨ Features

- 🔔 Smart notifications for **Fajr, Dhuhr, Asr, Maghrib, and Isha**
- 🌐 Bilingual messages (Arabic and English) – **fully editable**
- 🎨 Custom icons per prayer
- 📱 Compatible with both Android and iOS
- ✅ Interactive action buttons (Android only):
  - *Mark as Prayed*
  - *Snooze for 5 minutes*

---

## 📋 Prerequisites

Make sure the following are in place before using this blueprint:

1. **Islamic Prayer Times** integration is installed and correctly configured
2. You have the **Home Assistant Mobile App** installed and notifications enabled

---

## 🛠️ Setup Instructions

Click the button below to import the blueprint directly into your Home Assistant instance:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fshadynafie%2FAzanNotification%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fshadynafie%2Fazan_notifications.yaml)

---

⚙️ Configuration
Step 1: Create New Automation

Navigate to Configuration → Blueprints
Find "Azan Notifications v1.0"
Click Create Automation

Step 2: Basic Setup

Target Device: Select your mobile device from the dropdown
Prayer Sensors: Map each prayer to its corresponding sensor:

Fajr → sensor.fajr_prayer_time
Dhuhr → sensor.dhuhr_prayer_time
Asr → sensor.asr_prayer_time
Maghrib → sensor.maghrib_prayer_time
Isha → sensor.isha_prayer_time



Step 3: Prayer Preferences
Enable or disable individual prayers based on your needs:

✅ Fajr Prayer (Dawn)
✅ Dhuhr Prayer (Midday)
✅ Asr Prayer (Afternoon)
✅ Maghrib Prayer (Sunset)
✅ Isha Prayer (Night)

Step 4: Message Customization (Optional)
Personalize notification messages for each prayer:
Default: "Time for Fajr prayer – حان الآن موعد صلاة الفجر"
Custom: "🌅 Dawn prayer time has arrived - وقت صلاة الفجر"

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
