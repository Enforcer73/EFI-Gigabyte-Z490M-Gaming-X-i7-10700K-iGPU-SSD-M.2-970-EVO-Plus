# Gigabyte Z490M Gaming X + i7 10700K + iGPU + SSD M.2 970 EVO Plus
**Latest working macOS**: 12.6
<br>
**Current OpenCore**: 0.8.4
<br>
**SMBIOS**: iMac 20.1

## Complete hardware specs
- Intel i7 10700K
- iGPU UHD 630
- Gigabyte Z490M Gaming X
- 32Gb HyperX FURY DDR4 2666 MHz
- SSD M.2 Samsung 970 EVO Plus 500 Gb

## What works
- macOS Big Sur, macOS Monterey, macOS Ventura beta 7
- Audio
- HDMI/DP
- Apple GUC Intel UHD
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- Shutdown/Reboot/Update to newer macOS builds over time

## Kexts used:
- AppleALC.kext
- AppleNVMe.kext
- CPUFriend.kext
- CPUFriendDataProvider
- IntelMausi.kext
- Lilu.kext
- NVMeFix.kext
- RestrictEvents.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBPro.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Drivers used:

- OpenRuntime.efi
- HfsPlus.efi
- OpenCanopy.efi
- ResetNvramEntry.efi
- AudioDxe.efi
