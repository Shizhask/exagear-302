<h1 align="center">
  <br>
  <a href="#"><img src="https://raw.githubusercontent.com/XHYN-PH/exagear-302/main/logo/eltechs-sq-512-nopub.png" alt="ExaGear" width="370"></a>
  <br>
  <b>ExaGear: Windows Emulator</b>
  <br>
</h1>

<p align="center">
      <b><a href="https://github.com/XHYN-PH/exagear-302/issues">GAME COMPATIBILITY LIST</a> • <a href="#-downloads">DOWNLOAD</a></b>
</p>

<h4 align="center">ExaGear is a virtualization solution that provides an x86 emulation environment on ARM-based devices (●'◡'●).
</h4>

<p align="center">
    <a href="https://youtube.com/@xhyn_ph">
        <img src="https://img.shields.io/badge/YouTube-red?color=bd2c00&label=SUBSCRIBE&logo=youtube&logoColor=white"
            alt="YouTube">
     <a href="https://exagear.wiki">
        <img src="https://img.shields.io/badge/Wikipedia-%23000000.svg?color=6cc644&label=ExaGear&logo=wikipedia&logoColor=white"
            alt="Wikipedia">
     </a>
    <a href="https://discord.com/invite/q842JB4gCm">
        <img src="https://img.shields.io/discord/398318088170242053?color=5865F2&label=EmuGear&logo=discord&logoColor=white"
            alt="Discord">
    </a>
</p>

---

### ⚠️ WARNING
- **THE REAL PROJECT/DEVELOPMENT OF EXAGEAR EMULATOR IS ELTECHS AND IT'S BEEN CEASED/CLOSED SINCE FEB OF 2019.** For more information please visit the **[wiki](https://exagear.wiki)**
- I'm not the creator of any cache I modified. All files used on this cache is from respective owners/developers.

---

## ❓FAQ - Frequently Asked Question(s)
Question #1: **DOES EXAGEAR SUPPORTS X64 or 64-BITS ???**
- Absolutely No, It only supports x86 or 32-bits emulation, but you may want to check other alternatives such as **[Termux-Box](https://github.com/olegos2/termux-box)**, **[Box64Droid](https://github.com/Ilya114/Box64Droid)**, **[MoBox](https://github.com/olegos2/mobox)**, **[Winlator](https://github.com/brunodev85/winlator)**, **[Box4Droid](https://github.com/Herick75/Box4Droid)**, **[MiceWine](https://github.com/KreitinnSoftware/MiceWine)**, **[BRVM](https://github.com/Gamelover7825/BRVM)**, **[Fex-Android](https://github.com/AllPlatform/Fex-Android)**, **[androBox](https://github.com/Pipetto-crypto/androBox)**

Question #2: **IS EXAGEAR STILL SAFE TO USE ???**
- Maybe, Since ExaGear real developers has been stopped developing it, Only the community improving the project.
- It will be based on the cache/application you used since ExaGear has many mods across the internet.

Question #3: **DOES EXAGEAR SUPPORTS MALI-GPU ???**
- Absolutely Yes, Mali-GPU hardware acceleration is supported via VirGL only, but it's slow and only OpenGL (Other Alternative is Software Rendering)

Question #4: **WHY EXAGEAR INSTEAD OF OTHER EMULATORS ???**
- ExaGear is still the best for Old x86 Games and it has a very good touch controls unlike to other emulators, It's also one of the easiest to use...

---

### 📲 PHONE REQUIREMENTS
#### ANDROID VERSIONS 
(Minimum target is Android SDK Version 21 while Target is Version 27). 
> ⚠️ **Starting from Android 11 D:\ has been slowed and same to newer android versions**. On Huawei devices with Android 10 and above, there are problems running ExaGear.⚠️

| ANDROID VERSION | MIN API | SUPPORT | ISSUES |
| --------------- | ------- | ------- | ------ |
| Andorid 5.x     |      21 | UNKNOWN | UNKNOWN |
| Android 6.0     |      23 | SUPPPORTED | UNKNOWN |
| Android 7.x     |      24 | SUPPORTED | UNKNOWN |
| Android 8.x     |      26 | SUPPORTED | NONE |
| Android 9       |      28 | SUPPORTED | NONE |
| Android 10      |      29 | SUPPORTED | NONE |
| Android 11      |      30 | SUPPORTED | **SLOW D:\ DRIVE** |
| Android 12      |      31 | SUPPORTED | **KEYBOARD BUG (FIXED)** |
| Andorid 13      |      33 | SUPPORTED | **KEYBOARD BUG (FIXED)** |
| Android 14      |      34 | UNKNOWN | UNKNOWN |

#### COMPATIBLE GPU(s)
| GPU        | DDRAW | VIRGL OVERLAY | LLVM RENDERER | VIRTIO-GPU | TURNIP | ZINK | DXVK |
| ---------- | ----- | ------------- | ------------- | ---------- | ------ | ---- | ---- |
| Mali GPUs  | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO | NO | NO |
| PowerVR GPUs | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO | NO | NO |
| Adreno 5xx | SUPPORTED | SUPPORTED | SUPPORTED | NO | NO | NO | NO |
| Adreno 6xx | SUPPORTED | SUPPORTED | SUPPORTED | SUPPORTED | SUPPORTED | SUPPORTED | YES |
| Adreno 7xx | SUPPORTED | SUPPORTED | SUPPORTED | UNKNOWN | PARTIALLY | PARTIALLY | YES |

#### VIRGL OVERLAY
- VirGL Overlay uses `virgl-renderer` as the renderer. To run VirGL Overlay in Exagear, you need any graphics accelerator with support for **OpenGL ES 2.1(3.0)** and higher. Author of original development VirGL Overlay is [Mittorn](https://github.com/mittorn/virglrenderer-android), author of modifications is [alexvorxx](https://github.com/alexvorxx/VirGL-Overlay-Rebuild).
#### VIRTIO-GPU
- VirtIO-GPU in Exagear uses `virgl_vtest_server`, OpenGL renderer uses open drivers Turnip+Zink. To work, you need an Adreno 616+ graphics accelerator. Adreno 610,612 are not supported.
#### TURNIP
- [Turnip](https://www.exagear.wiki/index.php?title=Turnip) open source Vulkan driver for Adreno. It uses the files `/dev/kgsl-3d0`, `/dev/dri/card0` to access the GPU. It requires Adreno 610+ GPU to run.
#### ZINK
- [Zink](https://www.exagear.wiki/index.php?title=Zink) translator of Vulkan to OpenGL, it can be run on any GPU supporting Vulkan. It can be useful for GPUs that support Vulkan but do not have full OpenGL, using OpenGL ES instead.
#### DDRAW & LLVM
- DDRAW is part of windows from very old OS, It supported all devices. While LLVM is software renderer which is very slow but good compatibility.

Turnip+Zink are part of the Mesa drivers.

---

### 📄 INTRODUCTION
- What is ExaGear? A series of commercial programs created in 2013 by the Russian company Eltechs for translating x86_64 instructions into ARMv6(ExaGear Desktop),ARMv7 ,ARMv8 to run Windows applications and games in a Linux container using **[Wine](https://www.winehq.org/)** - a free implementation of the Windows API

### REASON FOR CLOSING THE PROJECT
- The reason for closing the project was **unprofitability**. After the release, the application was successfully hacked, and could be used for free, and apparently, sales of the application in the Play Market began to fall, from which the developers profits either dropped significantly or did not exist at all. Expensive controls for games played a role in the future of the project which closed on February 28, 2019.

---

### 📲 SCREENSHOTS

---

### ⚙️ FEATURES / CHANGELOGS

---

### 🪲 BUGS

---

### 📝 NOTES

---

### 🗨️ Feedback

---

### 🔗 DOWNLOADS

---

### 💿 MISCS/ESSENTIALS


---

### 🌐 COMMUNITIES

- [Alien's Community](https://t.me/exageartesting)
- [MishkaKolos Telegram](https://t.me/MishkaKolosExagear)
- [MishkaKolos Discord](https://discord.com/invite/qJ4HvDt)
- [ExaGear Allmod](https://t.me/exagearallmod)
- [Ajay's Community](https://discord.gg/XpbEp3dWv3)
- [Denis Rachev Community](https://t.me/denis_rachev2)
- [WEmu WIP](https://t.me/+IubWjXHbtScwOWQy)
- [Cassia WIP](https://discord.gg/XnbXNQM)
- [Project009's Community](https://discord.com/invite/GAg9eYg24G)
- [Box64Droid Discord](https://discord.gg/thjpZ4P7Bm)
- [Box64Droid Telegram](https://t.me/box64droidchat)
- [CoreLand's Community](https://t.me/CoreLand)
- [JotarOS Commmunity](https://t.me/EmulatorsROM)

---

### 📚 ACKNOWLEDGEMENTS

 - [Termux-X11 by @Twaik](https://github.com/twaik/)
 - [Windows Compatibility Layer by WineHQ](https://www.winehq.org/)
 - [EDPatcher by @bu2ub](https://github.com/ewt45/)
 - [Input-Bridge by @DotNetBurst](https://github.com/DotNetBurst/)
 - [3D Renderers by @alexvorxx](https://github.com/alexvorxx/)
 - [DXVK by @Doitsujin](https://github.com/doitsujin/dxvk)
 - [WineD3D For Windows by @Adolfintel](https://github.com/adolfintel/wined3d4win)
 - And ExaGear International Devs & Testers (Hugo, AkaGloomy, Luis Gaming Test, Ajay, Alien, CoreLand, MrPurple, Jump768, Sparda and Many More)
