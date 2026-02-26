---

# Realme Unified Tool Pro 🛠️

A powerful, modern Windows-based GUI toolkit designed for flashing, repairing, and optimizing Realme and compatible Android devices. Built with **Python** and **CustomTkinter** for a sleek, dark-mode experience.

---

## 🌟 Key Features

### ⚡ Device Diagnostics

* **Real-time Detection:** Instant ADB and Fastboot status.
* **Device Info:** Fetch Model, Android Version, Kernel, and Security Patch level.
* **Bootloader Status:** Check if your device is ready for flashing.

### 🔥 Advanced Flashing Engine

* **Port ROM (IMG) Flasher:** Specialized partition flashing (System, Product, Vendor, etc.) with smart logic for `my_manifest` variations.
* **Dirty vs. Clean Flash:** Choose between keeping data or a fresh start.
* **ADB Sideload:** Easy `.zip` flashing for Custom ROMs via Recovery (TWRP/OrangeFox).
* **Boot Image Utility:** One-click `boot.img` flashing for rooting or kernel updates.

### 🛡️ IMEI & Partition Tools (Root Required)

* **Safe Backup:** Backup critical network partitions: `nvram`, `nvdata`, `persist`, `nvcfg`, `protect1`, and `protect2`.
* **Restore:** Restore connectivity in one click if partitions get corrupted.

### 🧹 Maintenance & FRP

* **FRP Removal:** Fastboot-based Factory Reset Protection bypass.
* **Data Wipe:** Clean `userdata`, `metadata`, and `frp` partitions securely.

### 🔋 Battery Analytics

* **Dual Mode:** Supports both ADB (Standard) and `su` (Root) for deep health metrics.
* **Metrics:** View Design Capacity, Health %, Temperature, and Cycle Counts.

---

## 🖥️ Modern Command Panel

Access essential ADB and Fastboot commands through a dedicated GUI console:

* **ADB:** `devices`, `reboot`, `reboot-bootloader`, `reboot-recovery`, `fastbootd`.
* **Fastboot:** `devices`, `getvar all`, `reboot`, `erase partitions`.

---

## 🚀 Getting Started

### Requirements

* **OS:** Windows 10 or 11.
* **Device:** Unlocked Bootloader (for flashing) or Root Access (for system tools).
* **Setup:** USB Debugging enabled in Developer Options.
* **Hardware:** Use the original OEM USB cable for stability.

### Installation

1. Download the latest `Realme_Unified_Tool_Pro.zip` from the [Releases]([https://www.google.com/search?q=https://github.com/sairb1/Realme-Unified-Tool-Pro/releases](https://github.com/Sairb1/RealmeUnifiedToolPro/releases/tag/v5.3)) section.
2. Extract the folder to your Desktop.
3. Run `RealmeTool.exe`. **No installation required.**

---

## ⚠️ Disclaimer

> **IMPORTANT:** Flashing operations are inherently risky. Using this tool may void your warranty, erase your data, or brick your device if used incorrectly.
> **The developer (@imnotaino) is not responsible for any hardware damage or data loss.** Always maintain a backup of your important files before proceeding.

---

## 🤝 Credits & Support

* **Developer:** [Ayan (@imnotaino)](https://www.google.com/search?q=https://t.me/realme11x)
* **GitHub:** [sairb1](https://www.google.com/search?q=https://github.com/sairb1)
* **Community:** Join our [Telegram Channel](https://www.google.com/search?q=https://t.me/realme11x) for updates and support.

**Built With:**

* [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) - Modern GUI Library.
* [Google Platform Tools](https://developer.android.com/studio/releases/platform-tools) - ADB & Fastboot binaries.

---

<p align="center">Made with ❤️ for the Realme Community</p>
