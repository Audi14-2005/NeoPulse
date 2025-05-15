<!-- Typing animation using HTML (works in some GitHub README renderers or Markdown sites) -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=435&lines=🎒+NeoPack+-+IoT+Smart+Backpack" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://youtu.be/QEiaLV7WJts" target="_blank">
    <img src="https://img.youtube.com/vi/QEiaLV7WJts/0.jpg" alt="NeoPack Demo Video" width="60%" />
    <br/>
    📺 Watch Demo Video
  </a>
</p>

---

## 🧠 Abstract

**NeoPack** is a context-aware **IoT Smart Backpack** designed to enhance everyday efficiency and security.

> Forgetting books?  
> Caught in the rain?  
> Carrying a heavy bag?  
> **NeoPack** has your back — literally!

This system uses **ESP32 microcontrollers**, custom **EMI-triggered rails**, and a **mobile app** to deliver intelligent, real-time feedback—making your backpack smarter than ever.

---

## 💡 The Idea

In an era of smart everything, the **backpack** is still dumb.  
**NeoPack** redefines that.

- Books embedded with **ESP32-C3 modules**
- EMI-triggered rail system
- Weather forecasting
- Battery level and weight monitoring

📦 **NeoPack = Smart Alerts + Organized Packing + Real-Time Monitoring**

---

## 🎯 Objectives

- Detect missing books via **EMI-triggered ESP32-C3**
- Monitor battery levels of devices
- Detect overload conditions with a **load sensor**
- Get real-time alerts via the **NeoPulse mobile app**
- Retrieve contextual weather updates

---

## 🔍 Problems with Traditional Backpacks

- ❌ Can't verify packed books
- ❌ No weather-based alerts
- ❌ No battery status for internal devices
- ❌ No weight warnings
- ❌ No smartphone integration

---

## ✅ NeoPack’s Solution

- 📚 Book Tracking via **ESP32-C3** modules  
- 🌦️ Live weather forecasts to remind umbrella  
- 🔋 Battery level monitoring & alerts  
- ⚖️ Load sensing to avoid health issues  
- 📱 Fully integrated **NeoPulse app**

---

## 🔑 Key Features

### 1. 📚 Smart Book Tracking
No NFCs! Uses **EMI-triggered ESP32-C3 modules** embedded inside books to verify presence via Bluetooth.

### 2. 🌧️ Weather Alerts
Real-time forecasts from APIs alert users to carry umbrellas.

### 3. 🔋 Battery Monitoring
Tracks laptop/power bank battery levels and sends alerts.

### 4. ⚖️ Weight Detection
Load sensor checks if bag exceeds ergonomic safety thresholds.

### 5. 📲 NeoPulse Mobile App
Interactive dashboard showing status of books, battery, weight, and weather.

---

## 🛠 Hardware Components

| Component | Function |
|----------|----------|
| ESP32-S3 | Main controller (inside backpack) |
| ESP32-C3 | Embedded in books for detection |
| EMI Rail | Triggers books’ ESP32 modules |
| Load Sensor | Detects overweight condition |
| Battery Monitor | Monitors charge levels |
| Haptic Motor | Alert feedback |
| LED Indicator | Visual status indicator |

---

## 💻 Software Stack

- ⚙️ **NeoPulse Mobile App** (Dark/Light Mode)
- ☁️ **Supabase** for cloud sync
- 🔗 **REST APIs** for real-time communication
- 🌦️ **Weather API** for rain forecast
- 🔐 **SHA256 Authentication** for security

---

## 📱 NeoPulse App Screens

- 🏠 **Home**: System overview & alerts  
- 📚 **Books**: Packed/missing book status  
- 🌦️ **Weather**: Forecast & umbrella reminder  
- 🔋 **Battery**: Device charge status  
- ⚙️ **Settings**: App customization, themes

---

## 👨‍💻 Authors

| Name | ID |
|------|----|
| **Manoharan K** | 230701177 |
| **Monic Auditya A** | 230701194 |
| **Monish D Y** | 230701195 |

---

## 📄 License

This repository is for academic demonstration.  
Licensing terms will be defined in future production versions.

---

> _"Not just smart. Context-aware. Mission-ready. That’s **NeoPack**."_  
