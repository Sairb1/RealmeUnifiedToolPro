# 🛠️ Unified Tool Pro

A modern, high-performance Android flashing and repair toolkit for **Realme and compatible devices**, designed for speed, safety, and real-world usage.

---

## ⚡ Overview

Unified Tool Pro simplifies complex Android operations like flashing, partition management, and diagnostics into a **clean, powerful GUI experience**.

Whether you're flashing a ROM, fixing partitions, or debugging a device — everything is handled in one place.

---

## 🖥️ Requirements

| Requirement | Details                                |
| ----------- | -------------------------------------- |
| OS          | Windows 10 / 11 (64-bit), Linux, macOS |
| USB Driver  | ADB driver installed                   |
| Device      | USB Debugging enabled                  |
| Bootloader  | Unlocked (for flashing)                |

---

## 📦 Installation

### 🔽 Downloads

| Platform   | File                         |
| ---------- | ---------------------------- |
| 🪟 Windows | `UnifiedToolPro-Windows.exe` |
| 🍎 macOS   | `UnifiedToolPro-Mac.zip`     |
| 🐧 Linux   | `UnifiedToolPro-Linux`       |

---

### ⚙️ Setup

* **Windows:** Run `.exe` (no install needed)

* **macOS:** Unzip → Right-click → Open (first launch)

* **Linux:**
Download and rename it to "UnifiedToolPro" and then cd "directory" where tool located then run

  ```bash
  chmod +x UnifiedToolPro
  ./UnifiedToolPro
  ```

* Install ADB (Mac/Linux):

  ```bash
  sudo apt install google-android-platform-tools-installer
  ```

> ⚠️ PyInstaller builds may trigger false antivirus flags. Add exclusion if needed.

---

## 🚀 What’s New (v6.0)

* Stable flashing engine (Port + Stock)
* Fixed ADB/Fastboot reboot system
* Improved payload dumper reliability
* Cleaner UI and better interaction
* Reduced lag, flicker, and UI glitches

---

## 🌟 Features

---

### ⚡ Device Diagnostics

* Real-time ADB & Fastboot detection
* Device information:

  * Model
  * Android version
  * Kernel
  * Security patch
* Bootloader status check

---

### 🔥 Flashing Engine

#### 📦 Port ROM (IMG Flash)

* Flash custom `.img` files directly
* Dynamic partition rebuild support
* Only flashes **existing files** (safe logic)

---

#### 📱 Stock ROM (Payload / OTA)

* Extracts `payload.bin`
* Converts to `.img`
* Automatically flashes valid partitions

---

#### 📲 ADB Sideload

```bash
adb sideload rom.zip
```


### ⚡ Power Menu

Quick reboot controls:

* System → `adb reboot`
* Recovery → `adb reboot recovery`
* Bootloader → `adb reboot bootloader`
* Fastboot → `fastboot reboot`

---

### 🧩 Payload Dumper

* Load `payload.bin` or OTA zip
* View partitions
* Extract selected partitions

---

### 🛡️ IMEI & Partition Tools (Root)

Backup and restore:

* nvram
* nvdata
* persist
* nvcfg
* protect1 / protect2

---

### 🧹 Maintenance

* FRP removal
* Partition wipe:

  * userdata
  * metadata
  * frp

---

### 🔋 Battery Analytics

* ADB + Root support
* Displays:

  * Health %
  * Temperature
  * Cycle count
  * Design capacity

---

### 💻 CMD Studio

Run commands directly:

```bash
adb devices
fastboot devices
adb logcat
adb shell
```

---

## 🔄 Flashing Flow

### 🔥 Port ROM

```
IMG folder → fastbootd → rebuild partitions → flash → reboot
```

---

### 📱 Stock ROM

```
ZIP → payload.bin → extract → flash → reboot
```

---

## ⚠️ Disclaimer

Flashing operations can:

* Brick your device
* Wipe data
* Void warranty

Use at your own risk. Always keep backups.

---

* Developer: Ayan (@imnotaino)
* GitHub: sairb1

---

