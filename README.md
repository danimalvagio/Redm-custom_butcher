# 🥩 Advanced Butcher System for RedM (VORP)

An immersive and advanced butchering system for RedM servers using the VORP Framework. This script allows players to place a portable butcher table in the wild to process carcasses into meat and pelts, complete with realistic mechanics like meat spoilage and dangerous predator encounters.

---

## 📺 Video Preview
[![Watch the video](https://img.youtube.com/vi/EWnE-wN_HRE/0.jpg)](https://www.youtube.com/watch?v=EWnE-wN_HRE)
*Click the image above to watch the script in action.*

---

## 🔄 Choose Your Version

This repository contains two versions of the script. Both include the core immersive mechanics, but they differ in how they handle animal quality:

| Feature | **LITE** (Stable) | **FULL** (Beta) |
| :--- | :---: | :---: |
| **Portable Butcher Table** | ✅ | ✅ |
| **Meat Spoilage System** | ✅ | ✅ |
| **Predator Attacks** | ✅ | ✅ |
| **Standard Carcass Processing** | ✅ | ✅ |
| **Dynamic Quality/Star System** | ❌ | ✅ |
| **Quality-Based Rewards** | ❌ | ✅ |

### 🟢 LITE Version (Stable)
**The best choice for most servers.** It includes all the immersive features (spoilage and predators) but uses a standard carcass processing system. It's plug-and-play and works perfectly without needing complex star-rating detection.

### 🟡 FULL Version (Beta)
**For hardcore realism.** This version integrates with the animal's Quality System (Star Ratings). The rewards you get from butchering are dynamically calculated based on the specific quality (1, 2, or 3 stars) of the carcass you are processing. 

---

## ✨ Key Features

- **Portable Table**: Use the `butcher_table` item to spawn a processing station anywhere in the wild.
- **Realistic Spoilage**: Meat doesn't last forever! Items use a metadata-based timer. After a configurable time (default 2 hours), fresh meat turns into "Spoiled Meat".
- **Predator Risk**: Processing dead animals emits a scent. There is a configurable chance that dangerous wildlife (Wolves, Bears) will spawn and attack you while you are butchering!
- **Auto DB Setup**: The script automatically checks and inserts missing items into your `items` database table on resource start. No manual SQL execution required!
- **Highly Configurable**: You can easily change spoilage times, predator spawn chances, required items, and all UI translations via `config.lua`.

---

## 📦 Dependencies

- [vorp_core](https://github.com/VORPCORE/vorp_core)
- [vorp_inventory](https://github.com/VORPCORE/vorp_inventory)
- [oxmysql](https://github.com/overextended/oxmysql)

---

## 🛠️ Installation

1. **Download** the version you prefer (`custom_butcher_lite` or `custom_butcher_full`).
2. **Copy** the chosen folder into your server's `resources` directory.
3. **Add** `ensure custom_butcher` to your `server.cfg`.
4. *(Optional)* Import the provided `install.sql` into your database, or simply let the script auto-insert the items on the first server start.
5. **Restart** your server.

---

## 🎮 Usage

1. Give yourself a **Butcher Table** (admins can use `/testbutcher` to get the testing items).
2. Use the table from your inventory to place it on the ground in front of you.
3. Stand near the table with a valid carcass in your inventory.
4. Press **[E]** (default prompt) to process the carcass.
5. **Watch your back!** Bears or wolves might smell the blood and ambush you.

---

## 📜 Credits & License

- **Developer**: danimalvagio
- **License**: Feel free to use and modify for your server, but please keep the original credits intact.

---

## 💬 Support
If you find any bugs or have suggestions, feel free to open an Issue on GitHub or reply to the forum thread on Cfx.re!

