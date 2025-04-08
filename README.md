Root BlueStacks Air macOS
================

Tested on BlueStacks Air
- 5.21.680.7532
- 5.21.695.7506
- 5.21.700.7523
- 5.21.705.7515


![Screenshot](bluestacks-air-root-magisk.png)



## Requirements
- [BlueStacks Air](https://www.bluestacks.com/mac)
- [Kitsune Magisk](https://github.com/1q23lyc45/KitsuneMagisk/releases)  
  Tested version: v27.2-kitsune-4



## Rooting

> **Note:** Rooting may fail on mac with System Integrity Protection (SIP) enabled. Ask Google about [*How to disable SIP*](https://www.google.com/search?q=how+to+disable+sip) and Gemini will show you how to do it.

- Install BlueStacks Air
- ‼️ **REQUIRED** ‼️ Open BlueStacks Air for the first time
- Close BlueStacks Air
- Download this repo and extract it
- Copy the downloaded Kitsune Mask apk to the project folder, and rename it to `magisk.apk`
- Open **Terminal.app** or **iTerm.app** and navigate to the project folder
  ```bash
  cd ~/Downloads/root-bluestacks-air
  ```
- Execute `root.sh` with sudo
  ```bash
  sudo bash root.sh
  ```
- Wait until BlueStacks Air starts
- Install Kitsune Mask (`magisk.apk`)
- Open Kitsune Mask and press **OK** when the **Requires Additional Setup** prompt appears. This will reboot BlueStacks Air.
  ![magisk-additional-setup](magisk-additional-setup.png)
- Force quit BlueStacks Air if necessary
- Open BlueStacks Air and enjoy
- If you need **Zygisk**, enable it from Kitsune Mask settings and reboot BlueStacks Air



## Unrooting
- Make sure BlueStacks Air is closed
- Execute `unroot.sh` with sudo
  ```bash
  sudo bash unroot.sh
  ```
- Done



### Buy me a coffee
[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/hanreev)
