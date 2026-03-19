# 🛠️ Unified Tool Pro 

A modern, high-performance Android flashing and repair toolkit for **Realme and compatible devices**, built with Python and a refined architecture for stability, speed, and real-world usage.

---

## ⚡ What’s New?

* Stable flashing engine (Port + Stock)
* Fixed ADB/Fastboot reboot system
* Improved payload dumper reliability
* Cleaner UI with better interaction
* Reduced lag, flicker, and UI glitches

<img width="1439" height="854" alt="image" src="https://github.com/user-attachments/assets/b3a595a0-5720-4215-a9ec-86427dfd290c" />
<img width="1439" height="848" alt="image" src="https://github.com/user-attachments/assets/6cbd9b24-98bd-4ffe-b96f-f86e74acdf50" />




---

## 🌟 Features

### ⚡ Device Diagnostics

* Real-time ADB & Fastboot detection
* Device info:

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

* Extracts `payload.bin` from OTA
* Converts to `.img`
* Automatically flashes valid partitions

---

#### 📲 ADB Sideload

```bash
adb sideload rom.zip
```

---

#### 🥾 Boot Image Flash

```bash
fastboot flash boot boot.img
```

---

### ⚡ Power Menu

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

* Backup:

  * nvram
  * nvdata
  * persist
  * nvcfg
  * protect1 / protect2
* Restore partitions

---

### 🧹 Maintenance

* FRP removal
* Wipe:

  * userdata
  * metadata
  * frp

---

### 🔋 Battery Analytics

* ADB + Root support
* Shows:

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

## 🚀 Flashing Flow

### 🔥 Port ROM

```
IMG folder → fastbootd → delete partitions → recreate → flash → reboot
```

---

### 📱 Stock ROM

```
ZIP → payload.bin → extract → flash imgs → reboot
```

---

## ⚠️ Disclaimer

Flashing may:

* Brick your device
* Wipe data
* Void warranty

Use responsibly. Always keep backups.

---

## 🖥️ Requirements

* Windows 10 / 11
* Unlocked bootloader
* USB Debugging enabled
* OEM USB cable

---

## 📦 Installation

1. Download latest release
2. Extract ZIP
3. Run `RealmeTool.exe`

---

## 🤝 Credits

* Developer: Ayan (@imnotaino)
* GitHub: sairb1

---

---
