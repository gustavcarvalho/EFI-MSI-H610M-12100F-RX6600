# MSI H610M-B + i3 12100F + RX 6600 + AX210 Wifi Card

![Screenshot at Jul 13 07-50-10](https://github.com/gustavcarvalho/EFI-MSI-H610M-12100F-RX6600/assets/122801722/e65d5a78-d16d-411a-bb2b-3b2fb8f62e3a)

**Latest working macOS**: 13.4.1
<br>
**Current OpenCore**: 0.9.2

## Complete hardware specs
- Intel i3 12100f
- MSI H610M-B LGA 1700
- RX 6600 - AsRock
- 2x 8Gb DDR4 3200Mhz Juhor with XMP Enabled
- AX210 Wifi Card - Connected directly in the motherboard

## Notes
- I Removed the serial number, ROM and etc. Please generate a new one (MacPro1,1) with SMBios.
- I use the hackintosh with ReBar on. If you don't want to use please adjust in the config.plist
- Make the corrects configurations in your Bios
- Always remember to update the Wifi Card kext when you update OS

## What works
- Wifi
- Audio
- HDMI/DP (in dGPU)
- Nearly all the usb ports (Needs a better usb mapping)
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep? Never got the chance to test it, my hackintosh is up 24/7
- Bluetooth (Probably is the USBMap)
- Airdrop

## Kexts used:
- Airportltlwm.kext
- AppleALC.kext
- BlueToolFixup.kext
- CpuTscSync.kext
- IntelBluetoothFirmware.kext
- IntelBTPatcher.kext
- IntelMausi.kext
- Lilu.kext
- NVMeFix.kext
- RestricEvents.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext


## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 12th Intel Gen](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-12THGEN-ALDER-LAKE)


