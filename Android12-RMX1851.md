### AOSP Android 12.0 for Realme 3 Pro/X Lite

--------

#### Flashing Guide

* Note: Before flashing AOSP 12 your device must be on Realme UI 1.0 with unlocked Bootloader with TWRP Recovery
* [Unlock Bootloader](https://forum.xda-developers.com/t/guide-how-to-unlock-bootloader-install-twrp-gsi-and-magisk.3938845/) and flash Official [TWRP Recovery](https://dl.twrp.me/RMX1851/)
* Boot into recovery 
* Flash ROM, Gapps if needed
* Format Data
* Reboot to system

#### Changelog
Whats's working ?
* camera/video recordring 
* Flashlight 
* RIL
* Wifi
* Bluetooth
* Hotspot
* Gps
* Everything except below things..

Not working / Known Issues
* Fingerprint sensor
* Device Encryption
* Selinux is permessive :(
*  Device certification (CTS fails by default)

Note:
* You must format data and remove sdcard before installing it, do not insert sdcard again.
* If you insert sdcard then your recovery won't work anymore, if you do then solution is format data from fastboot mode (fastboot erase userdata)
* You can use any recovery.

#### Download link & version Tracker:
12-10-2021
#### ROM: [Fluid-2.0-Soda-UNOFFICIAL-RMX1851-20211011.zip](https://drive.google.com/file/d/1NR2ZtVK2dI2a03WD7V14Ab7K3T2Xkdx-/view?usp=sharing)
* Changelog: 
* Alpha 1.0 (initial build )

#### Contact:
* Developer: [iamsj7](https://t.me/iamsj7)
* Telegram Community & Support group: [Realme 3 pro](https://t.me/Realme3Pros)
