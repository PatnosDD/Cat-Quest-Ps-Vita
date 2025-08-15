# Port of Cat Quest for Ps Vita
This repository contains the necessary patches to create fully functional files for running Cat Quest on the PS Vita.

**IMPORTANT:** You must own **Cat Quest** on **Steam** to use this patch!  

---
### Known Issues  

- Lower FPS throughout the gameplay(20-30fps)

**If you want to support the project, you can leave a tip on one of those websites:**

Ko-Fi: https://ko-fi.com/patnosd

Patreon: https://www.patreon.com/PatnosD

PayPal: https://paypal.me/PatnosDD

Afdian: https://afdian.com/a/PatnosD

## PS VITA Set up

In order to have the best possible experience, I recommend you to use following plugin(s) (that you should be able to find somewhere on the net) :
- ioplus.skprx
 **+ Full CPU Overclock (500Mhz)**




## Instructions

### Prerequisites
1. Install the Cat Quest `.VPK` using **VitaShell** or download it straight from **VitaDB** on your PS Vita.  
   *Do not attempt to launch the game yet, as it will crash without the required files.*
2. Ensure you have purchased and downloaded the game from **Steam**;
3. Overclocking is necessary to run the game properly.

---

### STEAM VERSION
1. Visit the **Releases** page of this repository and download `CatQuestVitaSteam.zip`.
2. Extract the downloaded zip to a folder on your PC.
3. Copy the Steam game folder into the extracted folder.  
   **Note:** Your `CatQuestVitaSteam` folder should look like this:
```
   └── CatQuestVitaSteam/
    ├── Cat Quest/  <- ../steamapps/common/Cat Quest
    ├── vcdiff/
    ├── APPLYPATCH.bat
    ├── deterministic.exe
    └── xdelta3-x.x.x-x86_64.exe
```
4. Run `APPLYPATCH.bat` and wait for the process to complete (this can take 15–25 minutes depending on your system).
5. Once completed, you will see a file named `CatQuestVita.zip`.
6. Using **VitaShell**, connect your PS Vita to your PC and copy the extracted contents of `CatQuestVita.zip` (_zip file should be around 40-50MB_) to `ux0:app/CATS11111/`.
   **Note:** Your `CATS11111` folder on your Vita should look like this:
```
   └── CATS11111/
    ├── Media/
    ├── sce_module/
    ├── sce_sys/
    └── eboot.bin
```
7. if you encounter any issues take a look at the [Troubleshooting](#troubleshooting) section
8. Launch the game and enjoy!
---

### Troubleshooting
- Ensure that your PS Vita is properly overclocked.  
- Verify that you have the correct game version (Steam) and have followed the steps for your version.
- If `ux0:app` does not appear in File Explorer, make sure you have visibility of hidden directories enabled.

---

### Disclaimer
This patch requires a legally purchased copy of Cat Quest.

