# OC EFI MACOS MONTERY 12.7.5 ON HP ZBOOK 15 G3

This repository contains the necessary files and information to successfully boot macOS on this laptop. 

- Bootloader version: **OpenCore 1.0.0**
- SMBIOS: [MacBookPro13,1]
- Kexts version: everything up-to-date with the latest version
- macOS version: [Monterey 12.7.5](https://www.apple.com/macos/monterey)
- Remember to insert your SMBIOS info to config file before booting to your USB
![monterey](Screenshots/about.png)

## Specs

| Component         | Brand                                     |
|-------------------|-------------------------------------------|
| **CPU**           |  Intel Core i7-6820hq @ 2.7 GHz           |
| **iGPU**          |  Intel HD530 - SkyLake                    |
| **RAM**           |  16GB SODIMM 2133MHz                      |
| **Storage**       |  SSD Sandisk Sata 256GB                   |
| **Audio**         |  Realtek ALC236 - layout-id 13            |
| **WiFi/BT Card**  |  Intel AX210                              |
| **OS**            |  macOS Monterey 12.7.5                    |
| **BIOS**          |  N81 - The latest Bios 5/2023             |

## Bios Settings

| Option                            | Setup                     |
|-----------------------------------|---------------------------|
| **Secure Boot**                   |  off                      |
| **Legacy Support**                |  off                      |
| **Fastboot**                      |  off                      |
| **Network (PXE) Boot**            |  off                      |
| **Wake On LAN**                   |  off                      |
| **LAN/WLAN Auto Switching**       |  off                      |
| **Graphic Mode**                  |  Auto (disable NVIDA Card)|
| **Video memory size**             |  64MB                     |
| **Fingerprint Device**            |  off                      |
| **Extended Idle Power States**    |  off                      |
| **Deep Sleep**                    |  on                       |
| **Wake On USB**                   |  off                      |
| **Others**                        |  default                  |

## Tools

* [OpencorePKG](https://github.com/acidanthera/OpenCorePkg)
* [ProperTree](https://github.com/corpnewt/ProperTree)
* [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
* Check Kexts items and its version in the config file to get the right one on github source.

## Credits

* [Apple](https://apple.com) for macOS
* [Acidanthera](https://github.com/Acidanthera) for OpenCore and Lilu-based kexts 
* [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm) for Intel Wifi Card driver
* [dortania](https://github.com/dortania) team for its detailed guides
* And thanks to many nice guys on internet. 