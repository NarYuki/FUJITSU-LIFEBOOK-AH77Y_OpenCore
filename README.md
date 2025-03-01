# FUJITSU-LIFEBOOK-AH77Y_OpenCore
This is an example of OpenCore EFI for **LIFEBOOK AH77/Y**

富士通のMacを作りたい人の為に

## Spec
- CPU : Core i7-6700HQ
- iGPU : Intel HD 530
- Storage : SATA SSD 256GB
- Memory : 8GB
- Network : Intel Wireless 3165(WiFi&BT)
- OS : macOS Sonoma 14.5

## What works and not works
- ✅ : Works
- ✖ : Not Works
- 🤔 : unstable
## 

- ✅ACPI - sleeps, and wakes properly
- ✅iGPU - Intel HD 530 with full QE/CI support
- ✅Wi-Fi - working with the latest AirportItlwm
- ✅Bluetooth - works with Low Energy accessories
- ✅SD Card Reader - Read & Write supported
- ✅Synaptics Touchpad - fully functional with clicks and gestures
- ✅Function keys (F6 & F7 for brightness, F8 & F9 for volume) work correctly
- ✅Battery Status - able to fetch maximum capacity
- ✅Power management is working properly
- ✅SATA SSD/HDD support
- ✅Audio is working with the latest AppleALC installed
- ✅Continuity Camera works only over USB (this is known to happen even on real Macs)
- ✅iCloud services, including Find My, AirDrop, Handoff, AirPlay, and Sidecar, are working
- ✅Touch Panel - can be used after installing the [UPDD driver](https://www.touch-base.com/drivers).

- 🤔Display - display flickers after returning from sleep
