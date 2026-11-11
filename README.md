# 📱 GameHub Lite — Windows Android Emulator

<div align="center">
<br/>

[![Version](https://img.shields.io/badge/version-2.1.0-3A0CA3?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%2010%20%7C%2011-4361EE?style=for-the-badge&logo=windows11&logoColor=white)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/license-MIT-4CC9F0?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Size](https://img.shields.io/badge/size-%3C%20300%20MB-F72585?style=for-the-badge&logo=databricks&logoColor=white)](https://github.com)

<br/>

### 🎮 A lightweight Android emulator for Windows — built for gaming, not bloat

*⚡ Fast Boot • 🕹️ Gamepad Support • 🔧 Low RAM Usage • 🎨 Clean UI*

<br/>

<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD-3A0CA3?style=for-the-badge&logo=download&logoColor=white&labelColor=28067D" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-4361EE?style=for-the-badge&logo=rocket&logoColor=white&labelColor=2F49C7" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/📚_DOCS-4CC9F0?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=38A3C2" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="720" alt="maxresdefault - 2026-11-11T232710 965" src="https://github.com/user-attachments/assets/e48532f4-9d42-459a-b3f8-6d88d651a50c" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**GameHub Lite** is a **lightweight Android emulator** built specifically for running mobile games on Windows. Unlike heavy all-in-one emulators, it focuses on doing one thing well: **running games fast with minimal system impact**.

It uses hardware-accelerated virtualization (Hyper-V or HAXM), boots in seconds, and supports **keyboard mapping, gamepads, and multiple instances** — without the ads, bundled apps, or telemetry that plague mainstream emulators.

> ⚠️ **Important disclaimer:** This emulator is intended for **running games and apps you legally own**, running your own Android builds, and **legitimate development or testing purposes**. Do **not** use it to run pirated software or violate the terms of service of any app or game. You are responsible for complying with local laws and app store policies.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| ⚡ **Fast Boot** | 🕹️ **Gamepad Support** | 🔧 **Low Resource** |
|:---:|:---:|:---:|
| Cold boot in<br/>under 15 seconds | Xbox, DualShock<br/>& generic controllers | < 500 MB RAM<br/>at idle |

| 🎨 **Key Mapping** | 🗂️ **Multi-Instance** | 🛡️ **No Bloat** |
|:---:|:---:|:---:|
| Custom keyboard-to-touch<br/>mapping editor | Run multiple Android<br/>VMs side-by-side | No ads, no bundled<br/>apps, no telemetry |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why GameHub Lite

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Actually Lite** | A fraction of the size and RAM usage of mainstream emulators |
| 🎮 **Gamer-Focused** | Controller support, key mapping, and FPS overlay built in |
| 🚀 **Fast Boot** | Snapshot-based startup — resume sessions in under 3 seconds |
| 🛡️ **Clean & Private** | No ads, no tracking, no bundled software — ever |
| 🧩 **Open Architecture** | Supports custom Android images and AOSP builds |
| 🖥️ **Windows-Native** | Optimized for Windows 10/11 with Hyper-V acceleration |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 App Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📱  GameHub Lite  v2.1.0                        ║
╠══════════════════════════════════════════════════╣
║  🟢 Android 13 (API 33)  •  Running              ║
║  ──────────────────────────────────────────      ║
║  📊 Resources                                     ║
║  CPU: ████░░░░░░░░░░  28%                        ║
║  RAM: ███████░░░░░░░  1.8 / 4 GB                 ║
║  FPS: 60 (locked)       GPU: Hardware            ║
║                                                  ║
║  🎮 Gamepad: Xbox Controller (connected)         ║
║  ⌨️  Key Map: "FPS Default"                      ║
║  📁 Instances: 1 active  •  2 saved               ║
║                                                  ║
║  🚀 Boot time: 8.4s   💾 Snapshot: enabled       ║
║  🛡️ No ads   🔒 No telemetry                     ║
║                                                  ║
║  [ ▶ Start ]  [ ⏸ Pause ]  [ ⚙️ Settings ]       ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📱 gamehub-lite/
├── 🎯 src/
│   ├── emulator/              # Core emulation layer
│   │   ├── qemu-wrapper/
│   │   ├── gpu-bridge/
│   │   └── input-bridge/
│   ├── ui/                    # Desktop interface
│   ├── instances/             # Multi-VM manager
│   ├── mapping/               # Key & gamepad mapping
│   └── snapshots/             # Fast-boot support
├── 🎨 assets/                 # Icons & themes
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # Setup & troubleshooting
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%208-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D6?style=for-the-badge&logo=microsoft&logoColor=white)
![Windows](https://img.shields.io/badge/Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows11&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a game that won't run? Want to add support for more controllers or Android versions?

<div align="center">

<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-3A0CA3?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Y77gls81k0Dvxcsvx">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-F72585?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 📱 Made with 🎮 by the GameHub Lite Team

*If this emulator runs your games smoothly — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,12,27&height=120&section=footer" width="100%"/>

</div>
