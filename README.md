<!-- Header Typing Animation -->
<h1 align="center">
  <span style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; color: transparent;">NeoPulse Proudly Introduce NeoPack a SmartBag</span>
</h1>

> Which Autotake care of your Inventory. Provide insights and Reminders etc.

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&multiline=true&width=700&height=120&lines=🎒+NeoPack+-+IoT+Smart+Backpack;Smarter+Packing.+Safer+Days.+Connected+Life." alt="Typing SVG" />
</h1>

<!-- Video Preview -->
<p align="center">
  <a href="https://youtu.be/QEiaLV7WJts" target="_blank">
    <img src="https://img.youtube.com/vi/QEiaLV7WJts/maxresdefault.jpg" alt="NeoPack Demo Video" width="80%" style="border-radius: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.4);" />
  </a>
  <br/>
  📺 <b><i>Click to Watch the Demo</i></b>
</p>

---

<!-- Cool badge section -->
<p align="center">
  <img src="https://img.shields.io/badge/Platform-IoT-blue?style=for-the-badge&logo=raspberrypi" />
  <img src="https://img.shields.io/badge/Mobile-App-purple?style=for-the-badge&logo=flutter" />
  <img src="https://img.shields.io/badge/Cloud-Supabase-brightgreen?style=for-the-badge&logo=supabase" />
</p>

---

<!-- Fancy gradient block -->
<h2 align="center">
  🧠 <span style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; color: transparent;">Abstract</span>
</h2>

> **NeoPack** is a **context-aware IoT Backpack** that prevents forgetfulness, gives real-time feedback, and connects your essentials to your smartphone.

Forget forgetting.  
Forget the weather.  
Forget being overloaded.

**NeoPack = Smart + Safe + Aware.**

---

<h2 align="center">🌟 The Problem & Our Vision</h2>

<table align="center">
<tr>
<td width="45%">

### ❌ Traditional Backpacks

- No packing feedback
- No live status
- Not aware of weather
- No phone integration

</td>
<td width="10%" align="center">➡️</td>
<td width="45%">

### ✅ NeoPack

- 📚 Detects missing books  
- 🌦️ Alerts on rain forecast  
- 🔋 Tracks battery & weight  
- 📱 Syncs with mobile app  

</td>
</tr>
</table>

---

## 🔑 Key Features

| Feature | Description |
|--------|-------------|
| 📖 **Smart Book Tracking** | Detects books with ESP32-C3 via EMI rail |
| 🌦️ **Weather Sync** | Notifies if rain is expected today |
| 🔋 **Battery Monitoring** | Tracks laptop/powerbank charge status |
| ⚖️ **Weight Detection** | Load sensor for back safety |
| 📲 **NeoPulse App** | Control center in your pocket |

---

## 🛠 Hardware Stack

| Component | Role |
|----------|------|
| **ESP32-S3** | Master brain inside backpack |
| **ESP32-C3** | Book tags for detection |
| **EMI Rails** | Activates book modules |
| **Load Cell** | Detects bag weight |
| **Battery Monitor** | Monitors connected devices |
| **LED & Motor** | Feedback signals |

---

## 💻 Software Stack

```yaml
Frontend: React Native (NeoPulse App)
Backend: Supabase Realtime DB
Cloud: Weather API + Auth
Firmware: ESP-IDF (C/C++)
Security: SHA256 + Token-based auth
