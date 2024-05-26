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

- ✅Boots, sleeps and wakes
- ✅iGPU - Intel HD 530 with full QE/CI
- ✅Wi-Fi - using latest AirportItlwm
- ✅Bluetooth - working with Low Energy accessories
- ✅SDCard Reader - Read&Write
- ✅Synaptics Touchpad - click and gesture as perfect working
- ✅Function keys (F6 & F7 for brightness, F8 & F9 for volume, )
- ✅Battery Status - can fetch maximum capacity
- ✅Power management
- ✅SATA SSD/HDD
- ✅Audio is working with latest AppleALC installed
- ✅Continuity Camera works only over USB (that's known to happen also on real Macs)
- ✅iCloud Service with FindMy,AirDrop,Handoff,AirPlay and Sidecar is working

- 🤔Display - display flickers after returning from sleep
