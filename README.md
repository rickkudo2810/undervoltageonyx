
Poco F7 / Redmi Turbo 4 Pro Extreme Undervoltage and increase performance
# ⚠️ DISCLAIMER & WARNING - READ BEFORE PROCEEDING ⚠️

> [!IMPORTANT]
> **I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.** Please read the following carefully before applying these Undervolt (UV) profiles:

1.  **THE SILICON LOTTERY:** * Every chip is created differently. My Snapdragon 8s Gen 4 might be a "Golden Sample" capable of sustaining very low voltages (e.g., -128mV offset). **YOUR CHIP MIGHT NOT BE.**
    * Applying my exact settings blindly may cause immediate **Freezing, Reboots, or Bootloops**.

2.  **AGGRESSIVE PROFILE:**
    * This repository contains "Physical Limit" profiles.
    * **Retention Voltage is set to 16mV.** This is extremely low.
    * **Mid-range frequencies are undervolted by -128mV.**
    * Proceed with caution. I highly recommend you start with lower offsets (e.g., -50mV) and test your device's stability.

3.  **BACKUP IS MANDATORY:**
    * Always backup your `boot.img` and `init_boot.img` and `vendor.img` before flashing via Konabess.
    * Have a recovery method ready (TWRP, Fastboot) to restore the stock image if your device fails to boot.

4.  **SOFTWARE DEPENDENCY:**
    * These profiles are tested on **Xiaomi HyperOS 3(Android 16)**
**crDroid AOSP (Android 16)**.
 Compatibility with another AOSP or other ROMs is not guaranteed.
    * I recommend keeping **Joyose** and **Powerkeeper** enabled for thermal safety.

**YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.**
Table profile stock and UV here :
![1074](https://github.com/user-attachments/assets/274f9b63-587f-453e-9eb0-a6ae1a512b33)
**Instructions**
Install the Konabess v0.27.apk and run
Choose 0 for Snapdragon 8s Elite (Gen 4)
Choose Speed Bin 2 (0xf2) for change frequency and voltage Level
**Backup vendor_boot.img first** and copy to your PC
Edit like my profile - or add +1 Level Voltage when you do at first time
Repack and apply, do the reboot at same.
