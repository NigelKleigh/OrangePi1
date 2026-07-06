# Orange Pi One - Debian Installation

## Objective

Install Debian on an Orange Pi One using a microSD card.

---

## Software Used

- 7-Zip
- Balena Etcher
- Debian SD Card Images

---

## Files Downloaded

- boot-orange_pi_one.bin.gz
- debian-bookworm-armhf-ad9ev3.bin.gz

---

## Installation Steps

### 1. Download

Download:

- boot-orange_pi_one.bin.gz
- debian-bookworm-armhf-ad9ev3.bin.gz

---

### 2. Extract

Extract both `.gz` files using 7-Zip.

---

### 3. Combine

Open Command Prompt and combine the extracted images:

```cmd
copy /b tmp.img+ext4.img sd-card.img
```

---

### 4. Flash

Use Balena Etcher.

- Flash from file
- Select `sd-card.img`
- Select the SD card
- Click **Flash**

---

### 5. Boot

Insert the SD card into the Orange Pi One.

Connect:

- HDMI
- USB Keyboard
- 5V Barrel Jack Power

Debian boots from the microSD card.

---

## Lessons Learned

- Debian is a Linux distribution.
- `.gz` files are compressed.
- The Orange Pi boots from the SD card.
- A bootloader starts before Linux.
