# BPSRAssist

> **Blue Protocol: Star Resonance Assist** — Free companion overlay tool for Blue Protocol: Star Resonance

![Version](https://img.shields.io/badge/version-0.1.3.7--Preview-blue)
![Platform](https://img.shields.io/badge/platform-Windows_10/11-lightgrey)
![Price](https://img.shields.io/badge/price-Free-brightgreen)

---

## 📖 Overview

BPSRAssist is a lightweight desktop overlay companion for **Blue Protocol: Star Resonance**. It provides real-time dungeon mechanics visualization, automated task assistance, and detailed combat statistics — all rendered as transparent overlay widgets on top of the game.

**Free to use. No account required.**

---

## ✨ Features

### 🗺️ Minimap Overlay
- **Real-time dungeon mechanic visualization** — Rings, sectors, rectangles, lines, and polygons rendered on a custom minimap canvas
- **Supported dungeons:**
  - **S3 Raid** — Phase buffs, phase mapping, preset return, callouts, pinball, electromagnetic ring sequence
  - **S3 Sea Ringed Reef** — Matrix callout beams, ice/wave safe zones, pizza danger zones, duet color mechanics
  - **S3 Cursed Tomb** — Rectangle-based mechanics
  - **S3 Giant Tower** — Rectangle-based mechanics
  - **S3 Tina's Mindrealm** — Sector-based mechanics
- **Entity rendering** — Local player (dot + facing arrow), teammates (dot), bosses/monsters (triangle), dead teammates (faded red)
- **Configurable entity colors & sizes** — Customize per-kind via color picker and sliders
- **Layout overlays** — Arena grid lines, circles, squares, radial lines per dungeon

### ⚔️ Auto Combat
- Automated combat with configurable **lock position** and **radius limit**
- **Minimap ring overlay** (cyan) showing the combat zone
- Real-time stats: monsters killed, current target, home position

### ⛏️ Auto Gathering
- Automated resource gathering with **lock position** and **radius limit**
- **Minimap ring overlay** (green) showing the gathering radius
- Preview mode: ring displays before starting

### 🎣 Auto Fishing
- Automated fishing with catch/loss/rod-break statistics

### 📊 Overlay Widgets
| Widget | Description |
|--------|-------------|
| **Minimap** | Custom dungeon minimap with mechanic regions |
| **Game Tasks** | Task selector card (Fishing, Gathering, Combat) |
| **DPS Meter** | Real-time DPS statistics |
| **Buff Monitor** | Active buff/debuff tracking |
| **Debuff Monitor** | Incoming debuff alerts |
| **Boss DBM** | Boss mechanic timers |
| **Stats Monitor** | Character stat tracking |
| **Skill Log** | Skill cast history |
| **Spawn Tracker** | Monster spawn tracking |
| **Clock** | In-game time display |
| **Performance** | FPS and system metrics |
| **Notification** | In-app notification system |

### 📈 Analysis Pages
- **DPS Statistics** — Detailed damage analysis per encounter
- **Skill Breakdown** — Per-skill damage and usage statistics
- **Buff Tracker** — Historical buff/debuff data
- **Spawn Tracker** — Monster spawn pattern analysis
- **Module Optimizer** — Module recommendation engine

### 🔧 Additional Features
- **Game Launcher** — Start/close game via Steam or manual path (NA & SEA regions)
- **Hotkey system** — Configurable keyboard shortcuts
- **Auto-update** — Built-in update checking

---

## 🚀 Getting Started

### Requirements
- Windows 10/11 (x64)
- Blue Protocol: Star Resonance installed

### Installation
1. Download the latest release
2. Extract to a folder of your choice
3. Run `BPSRAssist.exe`
4. Configure server region (NA / SEA) and launch method (Steam / Manual Path)
5. Click **Start Game** or launch the game separately

---

## ⚙️ How It Works

BPSRAssist captures game data in real-time and renders overlay information on top of the game window. The minimap reads dungeon state, entity positions, buffs, and skill casts to display mechanic regions and warnings — helping you and your team navigate boss mechanics more effectively.

All settings are stored locally in `config.yaml` next to the executable. No data is sent to external servers.

---

## ⚠️ Disclaimer

- This tool is provided **as-is** for educational and personal use.
- Use at your own discretion and always check the game's Terms of Service.
- The developers are not responsible for any consequences arising from the use of this tool.

---

## 📄 License

Copyright © Natsuki. All rights reserved.

This software is provided free of charge for personal use. Redistribution, modification, or commercial use without explicit permission is prohibited.
