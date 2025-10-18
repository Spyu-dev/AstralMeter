# AstralMeter ⚡

<p align="right">
	<strong>English</strong> · <a href="README.pt-BR.md">Português</a> · <a href="README.es-ES.md">Español</a>
</p>

<div align="center">

[![GitHub](https://img.shields.io/github/downloads/Spyu-dev/AstralMeter/total?style=for-the-badge&color=%23280137)](https://github.com/spyu-dev/AstralMeter/releases/latest)

![Version](https://img.shields.io/badge/version-1.0.1-purple)
![License](https://img.shields.io/badge/license-AGPL--3.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-brightgreen)

[<img src="https://storage.ko-fi.com/cdn/kofi4.png?v=6" alt="Ko-fi" width="230"/>](https://ko-fi.com/spyudev)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png)](https://www.buymeacoffee.com/spyu)

**Professional DPS/HPS overlay for Star Resonance**

Track your combat stats in real time with a modern, customizable interface.

[📥 Installation](#-installation) • [✨ Features](#-features) • [⚙️ Settings](#-settings) • [🎮 How To Use](#-how-to-use)

</div>

---

## 📋 Prerequisites

> ⚠️ IMPORTANT: Install Npcap before launching AstralMeter.

### Npcap Setup

AstralMeter relies on Npcap to capture the game's network packets.

- Official download: https://npcap.com/#download
- Run the installer as Administrator
- Check "Install Npcap in WinPcap API-compatible Mode"
- Finish the installation and restart Windows

---

## 🚀 Installation

<p align="center">
	<a href="https://github.com/Spyu-dev/AstralMeter/releases/tag/v1.0.1"><strong>[CLICK HERE FOR METER DOWNLOAD]</strong></a>
</p>

1. Confirm Npcap is installed (see above)
2. Download the latest AstralMeter release from the button in the Release Notes section
3. Extract the `.zip` to any folder you prefer
4. Launch `AstralMeter.exe`

---

## ✨ Features

### 🎯 Real-Time Monitoring
- DPS (Damage Per Second)
- HPS (Healing Per Second)
- Total stats and player rankings
- High refresh rate (about every 100 ms)

### 🎨 Modern Interface
- Glassmorphism theme with subtle purple branding
- Adjustable transparency (opacity)
- Compact layout with smooth scrolling

### 🎨 Themes & Colors
- Theme selector available directly in Settings
- Available themes: Purple, Blue, Red, Orange, Cyan, Gray, Rainbow
- Rainbow theme auto-assigns colors per subclass for quick identification

### 🎭 Class Icons
- Dedicated icons for each specialization (subclass)
- Immediate visual cues aligned with the selected theme

### ⚡ View Modes
- Damage mode (DPS)
- Healing mode (HPS)
- Toggle via shortcut or on-screen switch

### 🧩 Compact Mode
- Shrinks bar height, margins, and scrollbar thickness
- Quick toggle: `Ctrl + M` (also available in Settings)
- Perfect for raids with many visible players

### 🌐 Languages
- Supported UI languages: Portuguese (pt), English (en), Spanish (es)
- Switch instantly within Settings

### 🎛️ Settings
- Window opacity control
- Show contribution percentage
- Auto-clear when switching servers
- Customizable keyboard shortcuts

### ⌨️ Default Shortcuts
- `Ctrl + ←` — Damage mode (DPS)
- `Ctrl + →` — Healing mode (HPS)
- `Ctrl + End` — Clear statistics
- `Alt` — Interact (toggle click-through)
- `Ctrl + ↑` — Scroll up
- `Ctrl + ↓` — Scroll down
- `Ctrl + M` — Toggle compact mode

All shortcuts can be customized from the Settings screen.

---

## ⚙️ Settings

Open Settings via the gear icon (⚙️) in the top-right corner.

### Appearance
- Window opacity from 30% to 100%
- Theme selection: Purple, Blue, Red, Orange, Cyan, Gray, Rainbow
- Enable or disable Compact Mode

### Behavior
- Auto-clear on server change
- Display contribution percentage

### Language
- Choose between pt, en, es (applies immediately)

### Keyboard Shortcuts
- Assign custom combinations for each action (DPS, HPS, clear, click-through toggle, scrolling)

How to remap a shortcut:
1. Click the shortcut field
2. Press the desired combination (e.g., `Ctrl + K`)
3. Click Save

---

## 🎮 How To Use

### First Launch
1. Start AstralMeter
2. Position the window (click-through is disabled initially)
3. The position saves automatically
4. Enter combat in-game to populate the meter

### Daily Use
1. Launch AstralMeter (it opens in the saved position)
2. Use `Alt` to toggle click-through when you need to interact
3. Rely on shortcuts to switch views and navigate the list

---

## 🔧 Tech Stack
- Electron (desktop app)
- Node.js
- Npcap (packet capture)
- Protocol Buffers (decoding)
- Zstd (decompression)

---

## 📝 License

AGPL-3.0 — see the LICENSE file for details.

---

## 🆘 Support
- Open an Issue to report bugs or request features
- Feedback and questions are always welcome

---

## 🙌 Contributors

Thanks to the people who contribute to this project:

- [Spyu](https://github.com/Spyu-dev)
- [Doufa](https://github.com/DoufaDev)