# CyberVision – Changelog

All notable changes to this project are documented in this file.  
For quick summaries, see Discord and Nexus.  
This file serves as the main and complete source of truth.

## [1.1.2] – Load Order update

### ⚙️  Remade some load order for the modlist in the Modlist.txt
- Some french Translation and conflict fix reorderin the 12 load order profiles.
- Before updating, make sure to back up your UserSettings.json to avoid rebinding everything.
- Path: CyberVision → Profiles → Selected profile → UserSettings.json
- Save-friendly.
- This is the last update for a while,, to me everything is set up properly now. 
- Waiting for feedback.

---

### 🔄 Mod Updates & Additions

**Update**
- All profiles Load Order
- Hotscene Full mod  

---

## [1.1.1] – Graphic and Visual Update

### ⚙️  Rework of the ENV and Reshade
- Exposure value was kinda broken in Path Tracing for whatever reason, i reworked the CyberVisionENV.
- Visual more stunning and less exposure change.
- Before updating, make sure to back up your UserSettings.json to avoid rebinding everything.
- Path: CyberVision → Profiles → Selected profile → UserSettings.json
- Save-friendly.

---

## [1.1.0] – Major Optimization Update

### ⚙️ General Optimizations
- Major optimization pass focused on CET-dependent mods.
- Reduced regular stutters, especially on low and medium-end setups.
- Stutters have been mostly eliminated at the cost of removing several non-essential mods.
- **Not save-friendly**: a new playthrough is strongly recommended.

**Important**
- Before updating, make sure to back up your `UserSettings.json` to avoid rebinding everything.  
  Path: `CyberVision → Profiles → Selected profile → UserSettings.json`

---

### 🔄 Mod Updates & Additions

**New**
- Non-Intrusive Minimap

**Fixes**
- Deceptious Bug Fix

**Outfits & Weapons**
- The RVCOON Dumpster 3  
- Virtual Atelier  
- Veegee Shop 3  

**Vehicles**
- Void Lotus Esprit  

**Additions**
- Rent a Motel  

**French Translations**
- Virtual Car Dealer  
- APEX Sonora Canyon  

---

### ❌ Removed (Performance Stability)
- Autoloot  
- Clean Effects  
- CorruptNCPD  
- CustomBlackWall  
- CyberwareStatsControl  
- No Cyberware Cost  
- Ricochet  
- Skip Anything  
- Smart Aim for Head  
- Stealth Runner  
- Taxi Work in Night City  
- Lean Anywhere / Sit Anywhere  
- Unlock Night City  
- SongBird Apartment  
- Vehicle Customizer  
- Time and Weather Aware – River Ward  
- Time and Weather Aware – Goro Takemura  
- Time and Weather Aware – Jackie Welles  
- Sexual Encounters – Clouds Nude Patch  
- Game v2.0 Patch – Quick Message Exit  
- Filter Saves by Lifepath and Type  
- Sandevistan Customization – Time Dilation  
- 1995 Porsche 993 RWB Rotana  

---

### 🔄 Replacements for Stability
- Ultra Plus **8.2 → 7.6**  
- Better Sleeves → Sleeves  
- Realistic Traffic Density **Very High → Ultra preset**  

---

### 🚗 Vehicle Optimization (Bin Cleanup)
Removed unnecessary `.bin` files from some vehicle mods to reduce CET memory usage.  
Vehicle colors are now handled via **CrystalCoat** instead.

Affected vehicles:
- BMW M4 CS 2018  
- Porsche 911 Targa 4 GTS 2025  
- 2019 Toyota Corolla  
- Ferrari F40 ZEPHYR  
- Ferrari F40 LB Works  
- Genesis X Gran Berlinetta  
- Mazda RX7 Fortune (Fast & Furious)  
- Mazda RX7 Initial D Stage 5  
- Mazda RX7 WBK  
- Mazda RX7 FD  
- 2021 Mercedes AMG  
- Nillu 27  
- Porsche 996 GT3  
- Porsche Singer 911 Armored  
- Volkswagen Super Beetle  
- Quadra Type-66 Phantom  

---

### 📦 Tweaks & Presets
- Camera adjustments for pistols and selected vehicles.
- RT/PT ShadowFix preset applied in vehicles (fixes arm shadow issues).
- ReShade tweak: reduced highlight values.
- Load order folder cleanup.
- All profiles updated to match new FOMOD changes.

---

## [1.0.1] – Stability & Visual Fixes

### ⚙️ UserSettings
- Updated `UserSettings.json` to enable **Color Precision** by default.  
  - Fixes cutscene fade issues and white flash screen.
- This was the **last update touching UserSettings**.  
  Please back up your file for future updates.

---

### 🔄 Mod Updates

**Fixes**
- CET NPC Body Tweaks  
- Autoloot  

**Graphics**
- Improved Vegetation LOD  
- General Shadow Fix  

**Outfits & Weapons**
- Yusei's Virtual Atelier  
- NC Fashion Virtual Atelier  
- Sabbath Virtual Atelier  

**Locations**
- Pacifica Apartment  
- Downtown Yacht  
- Corpo Rooftop Bar  
- Dogtown Car Meet  

**Additions**
- Lizzie Braindance  
- HotScenes  

---

### ❌ Removed
- Immersive Shooting AI (gameplay balance & performance reasons)
- Enemy Aggro Improvements (did not integrate well with the setup)
- Enemy Rarity Fixes (already handled elsewhere)
- Various forgotten downloads removed to reduce overall modlist size

---

### 🚀 Performance
- Minor overall performance tweaks
- Reduced stuttering on low and medium CPU/GPU configurations
