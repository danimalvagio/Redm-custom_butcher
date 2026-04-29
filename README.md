# 🥩 Advanced Butcher System for RedM (VORP)

An immersive and advanced butchering system for RedM servers using the VORP Framework. This script allows players to place a portable butcher table in the wild to process carcasses into meat and pelts, with realistic mechanics like spoilage and predator encounters.

---

## 🔄 Choose Your Version

This repository contains two versions of the script to suit different server styles:

| Feature | **LITE** (Stable) | **FULL** (Beta) |
| :--- | :---: | :---: |
| **Portable Butcher Table** | ✅ | ✅ |
| **Basic Processing** | ✅ | ✅ |
| **Quality/Star System** | ❌ | ✅ |
| **Meat Spoilage** | ❌ | ✅ |
| **Predator Attacks** | ❌ | ✅ |
| **Categorized Items** | ❌ | ✅ |
| **Recommended for** | Casual RP | Hardcore/Realistic RP |

---

## ✨ Features

- **Portable Table**: Use the `butcher_table` item to spawn a processing station anywhere.
- **Realistic Spoilage (Full only)**: Meat has a metadata-based timer. After a configurable time (default 2 hours), it turns into "Spoiled Meat".
- **Predator Risk (Full only)**: Processing animals has a chance to attract dangerous wildlife (Wolves, Bears).
- **Quality Integration (Full only)**: Better quality animals yield more/better resources.
- **Auto DB Setup**: The script automatically registers necessary items in your `items` table on resource start.
- **Highly Configurable**: Easily translate all messages and tweak timers/chances in `config.lua`.

---

## 📦 Dependencies

- [vorp_core](https://github.com/VORPCORE/vorp_core)
- [vorp_inventory](https://github.com/VORPCORE/vorp_inventory)
- [oxmysql](https://github.com/overextended/oxmysql)

---

## 🛠️ Installation

1. **Download** the version you prefer (**Lite** or **Full**).
2. **Copy** the folder into your server's `resources` directory.
3. **Import** the provided `install.sql` into your database (or let the script auto-insert items on first start).
4. **Add** `ensure custom_butcher` (or `custom_butcher_lite`) to your `server.cfg`.
5. **Restart** your server.

---

## 🎮 Usage

1. Get a **Butcher Table** (use `/testbutcher` as admin to give yourself one for testing).
2. Use the item from your inventory to place the table.
3. Stand near the table with a carcass in your inventory.
4. Press **[E]** (default) to process the carcass.
5. **Watch your back!** If using the Full version, predators might smell the blood.

---

## 📜 Credits & License

- **Developer**: danimalvagio
- **License**: Feel free to use and modify, but please keep the original credits.

---

## 💬 Support
If you find any bugs or have suggestions, feel free to open an Issue or contact me via the Cfx.re Forum!
