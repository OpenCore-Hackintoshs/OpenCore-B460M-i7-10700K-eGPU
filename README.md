# Specifications

Hardware List: https://pcpartpicker.com/b/x33tt6
```
Gigabyte B460M Aorus Pro (Bios: F4)
 - Audio: Realtek® ALC1200 codec
 - Ethernet: Intel® Ethernet Connection I219V12
Intel Core i7 10700K
Ram 2 x 16GB DDR4 2933 MHz
SSD WD BLACK SN750 1TB NVME PCIe Gen3 x4 (WDS100T3XHC)
Gigabyte Radeon RX 5700 GAMING OC 8GB - Navi 10
Wifi + Bluetooth Bcm94360cd
Monitor HP V225hz && DELL P2219H (3840x1080)
```

- OpenCore 0.7.6
- OS: macOS 12 x86_64
- Host: Hackintosh (SMBIOS: iMac20,2)
- Resolution: 1920x1080 @ FHDHz, 1920x1080 @ FHDHz
- WM: Spectacle

## Install

Download and extract the last release EFI.zip to your the root of your EFI partition and update your SMBIOS values.

For minor hardware differences, like processor and GPU, see the full guide:
https://dortania.github.io/OpenCore-Install-Guide/

---

**SMBIOS:** Mac BIOS Info, on hackintosh is about your Mac fake IDs and Serials.
You can use OpenCoreConfigurator to OpenCore 0.7.6 to generate:
https://github.com/ic005k/QtOpenCoreConfig/releases/tag/20220013

## MacOs Kexts

- [Lilu (1.5.8)](https://github.com/acidanthera/Lilu/releases/tag/1.5.8)
- [AppleALC (1.6.3)](https://github.com/acidanthera/AppleALC/releases/tag/1.6.3)
- [WhateverGreen (1.5.2)](https://github.com/acidanthera/WhateverGreen/releases/tag/1.5.2)
- [VirtualSMC (1.2.8)](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
- [SMCProcessor (1.2.8)](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
- [SMCSuperIO (1.2.8)](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
- [IntelMausi (1.0.6)](https://github.com/acidanthera/IntelMausi/releases/tag/1.0.6)
- USBInjectAll
- XHCI-unsupported

## Running OS

- Windows 11
- MacOs 12.0.1

## Working

- Wifi + Bluetooth (Airdrop, AirPlay)
- LAN Ethernet
- Boot Audio (Disabled)
- OS Audio
- USB Ports
- GPU Aceleration (Dual Monitor+)
- Temperature, Power Sensors
- iServices (DO NOT FORGET, use your own SMBIOS)
- Full Dev Environment (Web, Android, iOs)
- Etc

## Not Working

- RGB Control (Only work on Windows)

## Configs

![Bios Config](images/BiosConfig.jpg)
