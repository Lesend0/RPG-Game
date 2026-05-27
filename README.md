# ⚔️ Visual RPG (PyQt6 Edition)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![PyQt6](https://img.shields.io/badge/PyQt6-GUI-green?style=for-the-badge&logo=qt)
![Portfolio Project](https://img.shields.io/badge/Status-Portfolio_Project-orange?style=for-the-badge)

A lightweight, event-driven RPG game built with Python and PyQt6. This project demonstrates **Object-Oriented Programming (OOP)**, **Event-Driven UI architecture**, and **dynamic SVG rendering** for creating responsive, scalable graphics.

---

## ✨ Key Features

- **🎨 Dynamic SVG Rendering:** Game graphics (player, enemies, health bars) are generated mathematically in real-time via SVG XML, directly responding to game state changes—no static image files needed!
- **⚡ Event-Driven Architecture:** Leverages PyQt6's Signal and Slot mechanisms instead of traditional game loops for smooth, responsive UI interactions
- **🌍 Bilingual Support (i18n):** Full localization for **English** and **Russian**, cleanly separated from core logic
- **🎮 RPG Mechanics:** 
  - Progressive leveling system
  - Dynamic enemy scaling based on player level
  - Turn-based combat system with damage calculations
  - Shop system to upgrade equipment and potions
  - Health and resource management

---

## 🎯 Gameplay Screenshots

### Main Menu
![Main Menu](main_menu.png)
*Navigate between Fight, Shop, Stats, and Exit options*

### Combat System
![Combat](battle.png)
*Face challenging enemies with real-time health visualization and tactical choices*

### Shop
![Shop](shop.png)
*Purchase potions and armor to strengthen your character*

---

## 🛠️ Technical Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.x |
| **GUI Framework** | PyQt6 |
| **Graphics** | Dynamic SVG Generation |
| **Architecture** | Event-Driven, State Machine |
| **Packaging** | PyInstaller |

### Design Patterns
- **State Machine:** Menu → Fight → Shop → Death states
- **Event-Driven:** Signal/Slot for all user interactions
- **OOP Principles:** Encapsulation, inheritance, and polymorphism throughout

---

## 🚀 How to Play

### 🎁 Quick Start (No Python Required)
Perfect for recruiters and non-technical players!

1. Navigate to the [Releases](../../releases) tab
2. Download `Visual_RPG.exe`
3. Double-click and play! *(Windows only)*

### 💻 Run from Source (For Developers)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lesend0/RPG-Game.git
   cd RPG-Game
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the game:**
   ```bash
   python main.py
   ```

---

## 📋 Requirements

- Python 3.7+
- PyQt6
- *(See `requirements.txt` for full list)*

---

## 🎮 Game Mechanics

### Combat
- **Attack:** Deal damage to enemies
- **Heal:** Restore health points (limited potions)
- **Run Away:** Attempt to escape (success varies by situation)

### Progression
- Defeat enemies to gain experience and level up
- Higher levels unlock stronger enemies with better rewards
- Purchase upgrades in the shop to enhance combat effectiveness

### Shop System
- **Potions (10g):** Restore health during combat
- **Armor (200g):** Increases defense and survival chances

---

## 📦 Project Structure

```
RPG-Game/
├── main.py                 # Entry point
├── game/
│   ├── player.py          # Player class
│   ├── enemy.py           # Enemy generation and AI
│   ├── combat.py          # Combat logic
│   ├── shop.py            # Shop system
│   └── ui/
│       ├── svg_renderer.py # SVG graphics generation
│       └── gui.py         # PyQt6 interface
├── localization/
│   ├── en.json            # English translations
│   └── ru.json            # Russian translations
├── requirements.txt       # Dependencies
└── README.md
```

---

## 🎓 Learning Outcomes

This project showcases:
- ✅ Object-oriented design with inheritance and polymorphism
- ✅ Event-driven programming with signals and slots
- ✅ SVG rendering for scalable graphics
- ✅ State machine implementation for game flow
- ✅ Internationalization (i18n) best practices
- ✅ Game balance and progression systems

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs and issues
- Suggest new features or mechanics
- Improve code structure or performance
- Add additional languages

---

## 📄 License

This project is open source and available under the MIT License.

---

## 👤 Author

Created by **Lesend0** as a portfolio project demonstrating software engineering principles in game development.

---

**[⬆ Back to top](#-visual-rpg-pyqt6-edition)**
