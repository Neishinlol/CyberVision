<p align="center">
  <img src="https://i.ibb.co/qYQ9Pfr7/4-0.png" alt="CyberVision" width="100%">
</p>

<h1 align="center">CyberVision video from CV.06, thanks to you boss &lt;3</h1>

<p align="center">
  <a href="https://www.youtube.com/watch?v=4uQDSbVws0A">
    <img src="https://i.ibb.co/yc0M2P5r/thumbnail.jpg" alt="CyberVision video from CV.06" width="700">
  </a>
</p>

# CyberVision - Modern Realistic Modlist EN/FR

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-7289DA?logo=discord&logoColor=white)](https://discord.com/invite/WSFgf5S7wS) 
[![Patreon](https://img.shields.io/badge/Patreon-Support-F96854?logo=patreon&logoColor=white)](https://www.patreon.com/c/Neishin?vanity=user) 
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
![Game](https://img.shields.io/badge/Cyberpunk%202077-2.5%20%2B%20Phantom%20Liberty-FCEE0A)

---

Pour les français : https://github.com/Neishinlol/CyberVision-FR

## 📖 About
CyberVision is a **massive Cyberpunk 2077 modlist** with over **1500 mods**, designed for immersive gameplay and visual fidelity.  
Focuses on **roleplay, realism, and quality of life**, supporting **English and French** profiles.  
Balanced around **Normal difficulty**.  
✨ **HDR**, **DLSS 5** and **MFG** (frame generation for older GPUs) supported and included.

📚 **The full guide is on Discord**: installation, settings, mods info, DLSS 5 / HDR / MFG, keybinds, troubleshooting.  
👉 [CyberVision Discord](https://discord.com/invite/WSFgf5S7wS)

---

## 📋 Requirements
- **Cyberpunk 2077** official copy + **Phantom Liberty**
- Game version **2.5**
- A **pure, clean** game installation (see *Installation*)
- **[Wabbajack](https://www.wabbajack.org/)**
- **200 GB** of free space, on the **same drive** as the game
- **Nexus Premium** (highly recommended, otherwise every download is manual)
- **New game required** (no save from vanilla, another modlist, or CyberVision before `3.0.0`)

---

## ⚙️ Pre-Installation
Before installing CyberVision, complete the following steps:

### **Required Utilities**
- **.NET SDK** :  
  - [.NET 8.0 SDK - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)  
  - [.NET 9.0 SDK - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- **Microsoft Visual C++ Redistributable** (install both) :  
  - [x86](https://aka.ms/vc14/vc_redist.x86.exe)  
  - [x64](https://aka.ms/vc14/vc_redist.x64.exe)

### **Official Game Content**
- **Fresh install** of the game: uninstall, delete everything left in the game folder (and the folder itself), reinstall **Cyberpunk 2077 + Phantom Liberty**
- Launch it **once in vanilla** through the launcher, reach the main menu, quit
- **REDmod disabled**: remove the **REDmod DLC** in Steam / GOG, and **disable mods** in the game's launcher
- **Block automatic game updates**: a game update breaks the list

### **Overlays**
- Disable **all overlays** to avoid crashes: **Steam**, **Discord**, **RivaTuner / MSI Afterburner**, any other
  - Steam: Settings → In-Game → Uncheck “Enable Steam Overlay”  
  - OR Library → Cyberpunk 2077 → Right click → Properties → Uncheck “Enable Steam Overlay”  

### **Installation Location**
- Create a `CyberVision` folder at the **root of the same drive as the game**, e.g. `C:\CyberVision`
- **Do NOT install in** `C:\Program Files` or `C:\Program Files (x86)`  

### **Antivirus**
- Disable or remove 3rd-party antivirus (Webroot, Bitdefender…)  
- Add exclusions (Windows Defender included) for your **game folder** and your **CyberVision folder**

### **Pagefile / Virtual Memory**
Larger modlists require significant memory. Regardless of RAM/VRAM, this step is **required**:  
1. Press **Win + R** → `sysdm.cpl ,3` → Performance → Settings → Advanced → Virtual Memory → Change  
2. Uncheck "Automatically manage"  
3. Select fastest SSD → Custom size: `40960 MB` initial and max → Set → Apply → Restart  

### **NVIDIA Users**
- NVIDIA Control Panel → Manage 3D Settings → Shader Cache Size → Set to **10 GB** → Apply  
- **Disable G-Sync** when playing the list

---

## 🛠 Installation
1. Do all the **Pre-Installation** steps above
2. Run **Wabbajack**, link your **Nexus** account (⚙️ → Logins → Nexus Mods → Log In)
3. **Browse lists** → **Cyberpunk 2077** → tick **Non-Featured** → **CyberVision** → Install  
   (or **Install from Disk** with the `.wabbajack` file from Nexus / Discord)
4. **Installation Location**: `C:\CyberVision` (same drive as the game). **Download Location** fills in by itself
5. Click **Install** and let it finish (error? close Wabbajack and redo: it resumes where it stopped)
6. Run **ModOrganizer.exe** in your CyberVision folder, **pick your profile**, select **CyberVision** → **Run**  
   ⚠️ Always launch from **MO2**. The first launch is long.

For **setup instructions, configuration details, and troubleshooting**, check the **CyberVision Discord section**: [Discord Link](https://discord.com/invite/WSFgf5S7wS)

---

## 🎮 Profiles & Settings
6 profiles, **all plug and play** (Raster by default, turn on RT / PT in game if you use it):
- 01 - Potato - you can run vanilla Cyberpunk on a very old PC
- 02 - Standard - RTX 3070 / RX 6700 XT (raster) · RTX 4070 Ti (path tracing)
- 03 - Very High - RTX 4070 Ti / RX 9070 XT (raster) · RTX 5070 Ti (path tracing)
- 04 - FR - Potato
- 05 - FR - Standard
- 06 - FR - Very High

Set your **resolution** (1080p by default). Keep **FOV 95**, don't unlock the **60 FPS cap** (use frame gen), don't pick the **Phantom Liberty start**.

## 🌈 HDR Support
Supported: swap `CyberVision Reshade` for `CyberVision Reshade HDR` in MO2, then turn HDR on in game. Details on [Discord](https://discord.com/invite/WSFgf5S7wS).

## 🤖 DLSS 5 Support
Included and **disabled by default**, with two setups (**Ultra** / **Performance**) and their own ReShade. **Raster + DLSS 5** is the best looking combo. Setup on [Discord](https://discord.com/invite/WSFgf5S7wS).

---

## 📜 License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
