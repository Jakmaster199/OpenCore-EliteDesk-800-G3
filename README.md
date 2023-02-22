# **OpenCore 0.8.9 for HP EliteDesk 800 G3**

## Hardware Configuration

| Part               | Name                                   |
|--------------------|----------------------------------------|
| **Processor**      | Intel Core i3-7100U (7th Gen)          |
| **Memory**         | Hynix 2x8Gb DDR4 2300 MHz              |

***

## Features

- [x] USB Working
- [x] Both display ports
- [x] Full Audio support (Internal Speaker + SoundCard)
- [x] Ethernet (Sometimes it fails)
- [x] Graphics Acceleration
- [x] Boot chime

***

## BIOS Settings


***

## Included Kexts

| Name               | Description                            |
|--------------------|----------------------------------------|
| **AppleALC** | Native macOS HD audio for not officially supported codecs. |
| **IntelMausi** | Open Source driver for the Intel Network Cards. |
| **Lilu** | Kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS. |
| **NVMeFix** | Set of patches for the Apple NVMe storage driver, IONVMeFamily. Improve compatibility with non-Apple SSDs |
| **VirtualSMC** <br> **SMCProcessor** <br> **SMCSuperIO** | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning. |
| **WhateverGreen** | Patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. |
