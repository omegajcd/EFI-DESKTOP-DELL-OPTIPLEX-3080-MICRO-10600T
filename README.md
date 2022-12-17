# EFI-DESKTOP-DELL-OPTIPLEX-3080-MICRO-10600T
Dell Optiplex 3080 Micro 10600T

**Latest working macOS Ventura: 13.1
<br>
**Current OpenCore**: 0.8.7

## Complete hardware specs
- Intel i5 10600T
- ALC256/ALC3246
- 2x 4Gb DDR4 3200Mhz - 2666MHz
- Realtek RTL8168/8111

## What works
- macOS Big Sur, macOS Catalina and macOS Ventura (Tested)
- Audio
- HDMI/DP (in internal GPU UH630)
- All USB ports (USBs 3.0 work with XHCI-unsupported.kext)

## What doesn't work
- Sleep (Not Work)

## Kexts used:
- AppleALC.kext
- Lilu.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XHCI-unsupported.kext
- RealtekRTL8111.kext
- HibernationFixup.kext

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE
