<div align="center">

# 🕯️ Darkest Dungeon II | Persian Localization (پارسی‌ساز تاریک‌ترین دخمه ۲)
### *Official ParsiSaz Community Translation, Custom Fonts & Binary String Localization*

<br/>

[![ParsiSaz Portal](https://img.shields.io/badge/🌐_Documentation_Portal-parsisaz.github.io%2Fparsisaz-00f2fe?style=for-the-badge&logo=googlechrome)](https://parsisaz.github.io/parsisaz/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Locale](https://img.shields.io/badge/Locale-fa__IR-emerald?style=for-the-badge)](#-project-structure)
[![Maintainer](https://img.shields.io/badge/Maintained_by-Danial_Pahlavan-blue?style=for-the-badge&logo=github)](https://github.com/DanialPahlavan)

</div>

---

## 📖 Overview
This repository contains the Persian translation files, POT compilation tools, and localized binary assets for **Darkest Dungeon II** (by Red Hook Studios), structured according to the **ParsiSaz 2026 Game Localization Architecture (L10N-STD-2026)**.

---

## 🗂️ Project Structure (L10N-STD-2026)

```
DarkestDungeon-2---Persian/
├── loc/                           # Decoupled Core Localization Data
│   ├── templates/                 # Master string tables & source files
│   ├── fa-IR/                     # Persian translation catalog
│   └── glossaries/                # Dark fantasy, lovecraftian & psychological terminology
├── game_assets/                   # Game Engine Drop-in Directory
│   └── StreamingAssets/Localization/ # Localized binary assets
├── tools/                         # Automated Extraction & Compilation Scripts
│   ├── GenerateMO.bat             # Batch MO compiler
│   └── BuildPotFile               # POT generation utilities
├── HISTORY.md                     # Semantic Versioning Changelog
├── README.md                      # Project documentation
└── LICENSE                        # GNU General Public License v3
```

---

## 🚀 Installation Instructions

1. Download the latest pre-compiled release package from GitHub Releases.
2. Copy the contents of `game_assets/` (or `Binary/`) directly into your game directory:
   ```text
   <Darkest_Dungeon_II_Folder>/Darkest Dungeon II_Data/StreamingAssets/Localization/
   ```
3. Start the game. All narration subtitles, character memories, item descriptions, and user interface will appear in Persian.

---

## 🌐 Central Documentation & Bug Reports
For more details on engine hurdles, reverse engineering, and other games in the ecosystem:
👉 **[Open ParsiSaz Live Portal](https://parsisaz.github.io/parsisaz/)**
