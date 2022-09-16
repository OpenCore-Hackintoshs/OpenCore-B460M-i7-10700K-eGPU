# Specifications

Hardware List: https://pcpartpicker.com/b/x33tt6
```
Gigabyte B460M Aorus Pro (Bios: F4)
 - Audio: Realtek® ALC1200 codec
 - Ethernet: Intel® Ethernet Connection I219V12
Intel Core i7 10700K
Ram 2 x 16GB DDR4 2933 MHz
SSD WD BLACK SN750 1TB NVME PCIe Gen3 x4 (WDS100T3XHC)
AMD Radeon RX 460 2 GB
Wifi + Bluetooth Bcm94360cd
Monitor HP V225hz && DELL P2219H (3840x1080)
```

- [OpenCore 0.8.4](https://dortania.github.io/builds/?product=OpenCorePkg&viewall=true)
- OS: macOS 13 x86_64
- Host: Hackintosh (SMBIOS: iMac20,2)
- Resolution: 1920x1080 @ FHDHz, 1920x1080 @ FHDHz
- WM: Spectacle

## Install

Download and extract the last release EFI.zip to your the root of your EFI partition and update your SMBIOS values.

For minor hardware differences, like processor and GPU, see the full guide:
https://dortania.github.io/OpenCore-Install-Guide/

---

**SMBIOS:** Mac BIOS Info, on hackintosh is about your Mac fake IDs and Serials.
You can use OpenCoreConfigurator to OpenCore 0.7.8 (no one for 0.8.4 yet, but this version works) to generate:
https://github.com/ic005k/OCAuxiliaryTools/releases/tag/20220232

## MacOs Kexts

- [Lilu (1.6.3)](https://dortania.github.io/builds/?product=Lilu&viewall=true)
- [AppleALC (1.7.6)](https://dortania.github.io/builds/?product=AppleALC&viewall=true)
- [WhateverGreen (1.6.2)](https://dortania.github.io/builds/?product=WhateverGreen&viewall=true)
- [VirtualSMC (1.3.1)](https://dortania.github.io/builds/?product=VirtualSMC&viewall=true)
- [SMCProcessor (1.3.1)](https://dortania.github.io/builds/?product=VirtualSMC&viewall=true)
- [SMCSuperIO (1.3.1)](https://dortania.github.io/builds/?product=VirtualSMC&viewall=true)
- [IntelMausi (1.0.8)](https://dortania.github.io/builds/?product=IntelMausi&viewall=true)
- USBInjectAll
- XHCI-unsupported

## Running OS

- Windows 11
- MacOs 13 Beta 5

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
- RGB Control (With https://openrgb.org/)
- Etc

## Configs

![Bios Config](images/BiosConfig.jpg)
