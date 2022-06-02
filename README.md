# AMD Ryzen Hackintosh - Opencore EFI for Gigabyte AOURUS ELITE B550M series

## Specification

| **Component** | **Model**                     |
| ------------- | ----------------------------- |
| CPU           | AMD Ryzen 5 5600x @ 3.7GHz    |
| Motherboard   | Gigabyte AOURUS ELITE B550M   |
| RAM           | 16GB (2 x 8GB) @ 3200         |
| GPU           | AMD Radeon PowerColor RX 6600 |
| Ethernet      | RTL8118 2.5GbE                |
| OS Disk       | Kingston A2000 500GB          |

**macOS version**: Monterey 12.4

**OpenCore version**: 0.8.0

**SMBIOS**: MacPro7,1

![Screen Shot](https://raw.githubusercontent.com/Qinruiy/Opencore-Gigabyte-B550M/main/info.png)

## Drivers & Kexts

- [[Bootloader] OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [[Driver] HfsPlus](https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi)
- [[Kext] Lilu](https://github.com/acidanthera/Lilu)
- [[Kext] VirtualSMC](https://github.com/acidanthera/VirtualSMC)
- [[Kext] WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [[Kext] AppleALC](https://github.com/acidanthera/AppleALC)
- [[Kext] AppleMCEReporterDisabler](https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/Extra/AppleMCEReporterDisabler.kext.zip)
- [[Kext] AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] USBPorts](https://dortania.github.io/OpenCore-Post-Install/usb/manual/manual.html#usb-mapping-the-manual-way)

## Important Notes

- Please replace **PlatformInfo** > **MLB**,**SystemSerialNumber**,**SystemUUID**
