# 📥 Lunaris AOSP Installation Guide

> **Device:** Redmi K50i / POCO X4 GT (xaga)
>
> **ROM:** Lunaris AOSP v3.12

---

# 📋 Requirements

Before installing, ensure you have:

- ✅ Unlocked Bootloader
- ✅ Windows PC
- ✅ USB Cable
- ✅ Latest Xiaomi USB Drivers
- ✅ Battery above 50%

---

# 📦 Extract the ROM

Extract the downloaded **Lunaris AOSP Fastboot ZIP** to a folder on your PC.

The extracted folder should look similar to:

```text
lunaris_v3.12_xaga_fastboot
│
├── Boot/
├── images/
├── tools/
├── win_installation.bat
└── linux_installation.sh
```

---

# 🚀 Installation

### Step 1

Boot your Redmi K50i / POCO X4 GT into **Fastboot Mode**.

Power off the device.

Hold:

```
Volume Down + Power
```

until the Fastboot screen appears.

---

### Step 2

Connect the device to your PC using a USB cable.

---

### Step 3

Open the extracted folder.

Double-click:

```
win_installation.bat
```

---

### Step 4

The installer starts by asking whether you want to **Format Data**.

Choose one of the following:

```
Y = Format Data (Recommended)
N = Keep Data
```

A clean installation is recommended if:

- Installing Lunaris for the first time
- Switching from another ROM
- Experiencing issues after updating

---

### Step 5

Next, the installer asks you to choose your **Root** option.

```
1 = Without Root
2 = Flash with Magisk
```

Choose the option you prefer.

---

### Step 6

After your selections, the installer automatically:

- Detects the device
- Flashes all required partitions
- Installs Lunaris AOSP
- Reboots the device automatically

No additional commands are required.

---

# ⏳ First Boot

The first boot may take **2–5 minutes**.

This is normal.

Complete the Android setup wizard and enjoy Lunaris AOSP.

---

# ⚠️ Important Notes

- Do **not** disconnect the USB cable during installation.
- Do **not** close the installer while flashing.
- Ensure your battery is above **50%**.
- Use the latest Lunaris Fastboot package.

---

# 🆘 Need Help?

If you encounter any issues during installation, please open an issue on GitHub or contact the maintainer.

---

<div align="center">

### 🌙 Welcome to Lunaris AOSP

Built with ❤️ by **Rohan**

</div>
