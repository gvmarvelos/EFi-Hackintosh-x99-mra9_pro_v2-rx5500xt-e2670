# MRA9 PRO V2 + XEON E2670 V3 + RX 5500 XT

**Latest working macOS**: 13.0.1
<br>
**Current OpenCore**: 0.8.6

## Complete hardware specs
- Xeon e2670 v3 (not turbo activated)
- MRA9 PRO V2
- RX 5500 XT
- 2x 8Gb DDR4 2666Mhz 
- Wifi/BT (not installed)

## What works
- macOS Big Sur, macOS Ventura
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time
- Xcode 14
- Other development programs
- Dual boot with Windows 10

## What doesn't work
- Sleep

## Kexts used:
- AppleALC.kext
- Lilu.kext
- CpuTscSync.kext
- NVMeFix.kext
- RealtekRTL8111
- RestrictEvents
- SMCSuperIO.kext
- SMCProcessor.kext
- USBInjectAll.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XHCI-unsupported.kext

## Geekbench Results:

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)

## EMAIL
- gvmarvelos@gmail.com
