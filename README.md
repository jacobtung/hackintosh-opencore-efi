# Hackintosh Opencore EFI Setup

> jacob's opencore efi folder of GA-Z370N-WIFI hackintosh setup

## Hardware specs

- MB:Gigabyte Z370N WIFI ITX
- eGPU:SAPPHIRE RX580 8G PULSE
- CPU:Intel i5-8500
- HD:Samsung 970 EVO 500G
- Mem:CORSORI LPX DDR4 8G 3000 *2
- WIFI+BT:CM94360CS2 NGFF Module

## EFI folder structure
EFI
├── BOOT
│   └── BOOTx64.efi
└── OC
    ├── ACPI
    │   ├── SSDT-EC-USBX.aml
    │   ├── SSDT-HPET.aml
    │   └── SSDT-PLUG.aml
    ├── Drivers
    │   ├── AudioDxe.efi
    │   ├── HfsPlus.efi
    │   └── OpenRuntime.efi
    ├── Kexts
    │   ├── AppleALC.kext
    │   ├── IntelMausi.kext
    │   ├── Lilu.kext
    │   ├── SMCProcessor.kext
    │   ├── SMCSuperIO.kext
    │   ├── SmallTreeIntel82576.kext
    │   ├── USBMap.kext
    │   ├── VirtualSMC.kext
    │   └── WhateverGreen.kext
    ├── OpenCore.efi
    ├── Tools
    │   └── OpenShell.efi
    └── config.plist
## Notes

- Based on opencore version 0.66

- USB ports have been mapped as below showed

  ![2370N WIFI HACKINTOSH USB MAPPING](/Users/zhen/Desktop/2370N WIFI HACKINTOSH USB MAPPING.jpeg)

- you **DO NEED** fill your own fake-apple specs in config.plist **PlatformInfo** section
