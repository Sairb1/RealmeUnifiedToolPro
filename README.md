# 🛠️ Unified Tool Pro

A modern Android flashing and repair toolkit for Realme, OnePlus, and dynamic-partition devices — built for speed, control, and real-world usage.

<img width="1439" height="859" alt="Screenshot 2026-04-23 132533" src="https://github.com/user-attachments/assets/a16d1fae-4f68-41e2-8cc6-df0b9712c8e4" />
<img width="1388" height="512" alt="Screenshot 2026-04-23 132540" src="https://github.com/user-attachments/assets/4ebdab94-d1b5-4611-a46e-30484ad3a698" />


---

## ⚡ Overview

Unified Tool Pro simplifies low-level Android operations into a clean, powerful GUI:

- Flash ROMs (Port / Stock / GSI)
- Extract payloads & partitions
- Run ADB / Fastboot commands
- Work with OTA packages directly

Everything in one place — no tool switching.

---

## 🖥️ Requirements

- OS: Windows 10 / 11 (64-bit)
- Drivers: ADB / Fastboot installed
- Device: USB Debugging enabled
- Bootloader: Unlocked (for flashing features)

---

## 📦 Installation

### Downloads

- Windows → UnifiedToolPro.exe

---

### Setup

Windows:
- Run the .exe (portable)


---

## 🚀 What’s New (v6.5)
<img width="1439" height="844" alt="Screenshot 2026-04-23 132551" src="https://github.com/user-attachments/assets/20b60970-2dbd-401a-83e4-1a6cf7e17c9c" />
<img width="1439" height="828" alt="Screenshot 2026-04-23 132616" src="https://github.com/user-attachments/assets/9d90c6f3-e5b2-4f4d-be0b-60df06f81156" />
<img width="1439" height="837" alt="Screenshot 2026-04-23 132606" src="https://github.com/user-attachments/assets/d0cc24db-a42c-4411-8103-c654173fa930" />

- Improved Stability
  - New Animations and transitions
  - Reduced crashes (threads / tasks)
  - Better flashing reliability

- UI Improvements
  - Cleaner layout
  - Fixed light theme visibility
  - Better interaction flow

---

## 🌟 Features

### Device Diagnostics

- Real-time ADB / Fastboot detection
- Device info:
  - Model
  - Android version
  - Kernel
  - Security patch
- Bootloader status

---

### Flashing Engine

#### Port ROM (IMG Flash)

- Flash .img files directly
- Dynamic partition rebuild
- Safe flashing (only existing files)

---

#### Stock ROM (Payload / OTA)

- Extract payload.bin
- Convert to .img
- Flash valid partitions automatically

---

#### Permanent GSI Flasher (Advanced)

- Deletes and rebuilds system partitions
- Flashes GSI as primary system

⚠️ High-risk operation  
No fallback system — use only if you understand dynamic partitions

---

#### ADB Sideload

adb sideload rom.zip

Safest method for official updates.

---

### Payload Dumper

- Load payload.bin or OTA ZIP
- View partitions
- Extract selected images

---

### Partition / IMEI Tools (Root)

Backup & restore:

- nvram
- nvdata
- persist
- nvcfg
- protect1 / protect2

---

### Maintenance

- FRP removal
- Partition wipe:
  - userdata
  - metadata
  - frp

---

### Battery Analytics

- Health %
- Temperature
- Cycle count
- Design capacity

---

### CMD Studio

adb devices  
fastboot devices  
adb shell  
adb logcat  

---

## 🔄 Flashing Flow

Port ROM:
IMG → fastbootd → rebuild → flash → reboot

Stock ROM:
ZIP → payload.bin → extract → flash → reboot

OTA Link:
Paste link → detect → extract / download → flash

GSI:
fastbootd → delete partitions → recreate → flash system

---

## ⚠️ Disclaimer

This tool performs low-level operations.

You can:
- Brick your device
- Lose data
- Break partitions

Always:
- Backup first
- Verify files
- Use correct images

---

## 👤 Developer

Ayan (@imnotaino)  
GitHub: sairb1

---
