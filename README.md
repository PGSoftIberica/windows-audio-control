<div align="center">

# 🎚️ Audios

### Ultimate Audio Control for Windows

<p align="center">
  <img src="https://img.shields.io/badge/Windows-10|11-0078D4?logo=windows&logoColor=white&style=for-the-badge" alt="Windows"/>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white&style=for-the-badge" alt="Python"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/Open_Source-❤️-red?style=for-the-badge" alt="Open Source"/>
</p>

---

## ✨ Features

### 🎛️ Core
- Per-app volume — Control every application individually
- Master volume — System-wide control + mute
- System tray — Quick access from notification area
- Device switching — Seamless headphone/speaker toggle
- Peak meters — Real-time audio levels
- Balance control — Left/right adjustment

### 🔥 Advanced
- Audio routing — Route apps to different outputs
- Virtual devices — Create virtual inputs/outputs
- 10-band EQ — System-wide equalizer with presets
- Audio effects — Compressor, limiter, noise gate
- Mic monitoring — Hear yourself with effects
- Noise suppression — Filter background noise

### ⚙️ Profiles & Automation
- Unlimited profiles — Gaming, Work, Movie, etc.
- Auto-switch — Trigger profiles by app or time
- Volume ducking — Auto-lower music during voice chat
- Scheduled actions — Change settings at specific times

### ⌨️ Hotkeys
- Custom hotkeys for every action
- Volume control, mute, profile switching
- Device toggling
- Mouse button support

### 🎨 Interface
- Dark/light themes
- Compact & expanded modes
- App grouping (browser tabs)
- Toast notifications

---

## 📦 Download

[![Download](https://img.shields.io/badge/Download-v2.1.0-blue?style=for-the-badge&logo=windows)](https://github.com/yourusername/Audios/releases/latest)

ZIP contains: Audios.exe + config file. No installers, no registry changes.

> ⚠️ Antivirus note: Executable not digitally signed (costly). May trigger false positives. Source code is open for inspection. Build from source if concerned.

---

## 🚀 Quick Start

1. Download latest Audios.zip from Releases
2. Extract to any folder
3. Run Audios.exe
4. Find 🎚️ icon in system tray
5. Double-click to open control panel

---

## 🛠️ For Developers

### Stack
- Python 3.10+
- pycaw — Audio hardware control
- PySide6 — GUI framework
- pystray — System tray

### Build from source
```bash
git clone https://github.com/yourusername/Audios.git
cd Audios
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python src/main.py

# Build executable
pip install pyinstaller
pyinstaller --onefile --windowed src/main.py
