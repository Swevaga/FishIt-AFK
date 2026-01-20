# FishIt-AFK

<div align="center">

![GitHub Stars](https://img.shields.io/github/stars/Evaga/FishIt-AFK?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows_RDP-blue?style=for-the-badge)
![Game](https://img.shields.io/badge/Game-Roblox_Fish_It!-red?style=for-the-badge)

**Automated AFK Farming Environment for Roblox "Fish It!" via RDP/VPS.**

</div>

---

## 📖 Overview

**FishIt-AFK** is a comprehensive setup guide and resource repository for running an automated AFK (Away From Keyboard) farming system on a Windows RDP environment. Specifically optimized for the Roblox game **"Fish It!"**, this repository provides all the necessary runtimes, software, and scripts to ensure a stable farming session.

---

## 🛠 Required Runtimes & Drivers

To run Roblox and executors smoothly on an RDP, you **must** install these essential components first:

| Software | Purpose | Download Link |
| :--- | :--- | :--- |
| **.NET 10.0** | Core Application Framework | [Download](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) |
| **Visual C++** | All-in-One Runtimes (Dec 2025) | [Download](https://www.mediafire.com/file/cph8o5afqlu9eub/Visual-C-Runtimes-All-in-One-Dec-2025.zip/file) |
| **DirectX** | End-User Runtime | [Download](https://www.microsoft.com/en-US/download/details.aspx?id=35) |
| **Runtime 21730** | System Dependency | [Download](https://www.mediafire.com/file/52myojdb9bazpix/runtime21730.rar/file) |

---

## 🎮 Game & Emulator Setup

1.  **Roblox Player:** Install the official client [here](https://www.roblox.com/download).
2.  **BlueStacks:** (Optional) If you prefer mobile emulation for lower resource usage, download it [here](https://www.bluestacks.com/id/index.html).
3.  **Xeno Executor:** Use [Xeno](https://www.xeno.onl/) to inject and run scripts.

---

## 📜 Automation Scripts

Copy and execute these scripts within your executor once the game has loaded:

### 1. LS Hub (Fish It! Keyless)
The primary automation script for farming:

loadstring(game:HttpGet("[https://rawscripts.net/raw/Fish-It!-LS-Hub-Keyless-71754](https://rawscripts.net/raw/Fish-It!-LS-Hub-Keyless-71754)"))()

2. Infinite Yield FE
For administrative commands and utility:

Lua

loadstring(game:HttpGet('[https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source](https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source)'))()
loadstring(game:HttpGet("https://raw.githubusercontent.com/4LynxX/Lynx/refs/heads/main/LynxxMain.lua"))()


🚀 How to Start Farming
Deploy RDP: Use the VPSBYEVAGA workflow to get your 3-hour RDP session.

Install Essentials: Download and install all links in the Required Runtimes section.

Launch Game: Open Roblox and enter the "Fish It!" game.

Inject & Run: Open your executor (Xeno), paste the LS Hub script, and execute.

Configure AFK: Set your in-game preferences and let the system farm for you.

⚠️ Disclaimer
This repository is for educational and personal use only. Using third-party scripts in Roblox violates their Terms of Service. Evaga is not responsible for any account bans or data loss resulting from the use of these tools. Use alternative accounts (alts) for farming.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

<div align="center"> Developed with 🎣 by <a href="https://www.google.com/search?q=https://github.com/Evaga">Evaga</a> </div>


-----

### Mengapa README ini Bagus?

1.  **Tabel Runtimes:** Mengelompokkan link Mediafire dan Microsoft Anda ke dalam tabel rapi agar pengguna tidak bingung mana yang harus diinstal duluan.
2.  **Code Blocks:** Script *loadstring* diletakkan di dalam blok kode hitam agar mudah di-copy hanya dengan satu klik.
3.  **Disclaimer Teknis:** Menambahkan peringatan tentang penggunaan akun "Alt" (alternatif) membuat Anda terlihat seperti pengembang yang berpengalaman dan peduli pada keamanan pengguna.

**Langkah Terakhir:**
Masukkan semua link tersebut ke dalam file `README.md` di repositori **FishIt-AFK**. Apakah Anda ingin saya membantu membuatkan file **Folder Structure** untuk menyimpan link-link ini secara offline di dalam repo?
