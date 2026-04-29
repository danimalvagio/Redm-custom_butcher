# 🥩 Advanced Butcher System for RedM (VORP)

An immersive and advanced butchering system for RedM servers using the VORP Framework. This script brings realism to your hunting sessions with realistic meat spoilage and dangerous predator encounters attracted by the smell of blood.

---

## 📺 Video Preview
[![Watch the video](https://img.youtube.com/vi/EWnE-wN_HRE/0.jpg)](https://www.youtube.com/watch?v=EWnE-wN_HRE)
*Click the image above to watch the script in action.*

---

## 🔄 Choose Your Version

This repository contains two versions of the script to suit your server's needs:

| Feature | **LITE** (Stable) | **FULL** (Beta) |
| :--- | :---: | :---: |
| **Butcher Carcasses** | ✅ | ✅ |
| **Meat Spoilage System** | ✅ | ✅ |
| **Predator Attacks** | ✅ | ✅ |
| **Standard Processing** | ✅ | ✅ |
| **Dynamic Quality System** | ❌ | ✅ |
| **Quality-Based Rewards** | ❌ | ✅ |

### 🟢 LITE Version (Stable)
**The best choice for most servers.** It includes all the immersive features (spoilage and predators) but uses a standard carcass processing system. It's plug-and-play and works perfectly without needing complex star-rating detection.

### 🟡 FULL Version (Beta)
**For hardcore realism.** This version integrates with the animal's Quality System (Star Ratings). The rewards you get from butchering are dynamically calculated based on the specific quality (1, 2, or 3 stars) of the carcass.

---

## ✨ Key Features

- **Realistic Spoilage**: Meat doesn't last forever! Items use a metadata-based timer. After a configurable time (default 2 hours), fresh meat turns into "Spoiled Meat".
- **Predator Risk**: Processing dead animals emits a scent. There is a configurable chance that dangerous wildlife (Wolves, Bears) will spawn and attack you while you are butchering!
- **Auto DB Setup**: The script automatically checks and inserts missing items into your `items` database table on resource start. No manual SQL required.
- **Highly Configurable**: Easily change spoilage times, predator spawn chances, rewards, and all UI translations via `config.lua`.

---

## 📦 Dependencies

- [vorp_core](https://github.


