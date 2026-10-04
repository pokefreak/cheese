# Cheese (WoTLK 3.3.5)

**Cheese** is a visual notification addon for **World of Warcraft: Wrath of the Lich King (Patch 3.3.5)** [0.6.4, 0.6.15]. It brings modern, Cataclysm-style visual spell alert overlays and proc bars to your classic 3.3.5 interface, keeping you informed the exact moment your crucial talents or buffs trigger [0.6.4].

---

## ✨ Features

- **Visual Spell Alerts:** Displays distinct, high-quality modern overlays around your character when vital spells or talents proc [0.6.4].
- **Proc Progress Bars:** Tracks the duration of active procs dynamically to optimize your rotation window [0.6.4].
- **Feral Druid Fixes:** Fully compatible with Feral Druids, including precise tracking for *Predator's Swiftness* [0.6.4].
- **Lightweight & Fast:** Coded purely in Lua specifically optimized for the 3.3.5a client [0.6.7, 0.6.14].
- **Macro Support:** Includes structural elements allowing for reliable macro configurations (`CheeseDKMacro`) [0.6.4].

## 📦 Installation

Follow these quick steps to get Cheese running in your client:

1. **Download** the repository or release archive [0.6.8].
2. **Extract** the files from the zipped package [0.6.1].
3. **Move** the `Cheese` folder into your World of Warcraft directory:
   ```text
   World of Warcraft/Interface/AddOns/
   ```
4. Ensure the directory path looks like `World of Warcraft/Interface/AddOns/Cheese/` (make sure there are no nested folders inside matching this name) [0.6.1].
5. **Restart** or log into World of Warcraft, click the **AddOns** button on the bottom left of your character select screen, and ensure **Cheese** is checked [0.6.1].

## 🔧 Commands

Configure your triggers or position overlays directly using in-game slash commands:

- `/cheese` — Opens the main configuration interface.
- `/cheese config` — Opens settings panel to customize overlays, scale, and transparency.
- `/cheese test` — Toggles mock overlays so you can reposition and adjust them on your UI.

## 🤝 Contributing

Contributions, bug reports, and custom layout profiles are welcome! 

1. Fork the Repository.
2. Create a Feature Branch (`git checkout -b feature/NewProcAlert`).
3. Commit your changes (`git commit -m 'Add proc tracking for specific spec'`).
4. Push to the Branch (`git push origin feature/NewProcAlert`).
5. Open a Pull Request.

## 📜 License

This project is licensed under the MIT License - see your local project files for details.
