# Deskmini Hackintosh

![os-img](resources/os.png)

## Tech Specs

* OS: macOS Catalina 10.15.x (SMBIOS: Macmini8,1)
* OpenCore: 0.5.9
* CPU: Intel i5-9400
* GPU: Intel UHD Graphics 630
* SSD: Kioxia RC10 500G
* RAM: ADATA DDR4 2666 8GB x 2
* Wi-Fi & Bluetooth: BCM94360CS2
* Monitor: DELL P2415Q

## Works

* Ethernet ✅
* Wi-Fi ✅
* Bluetooth ✅
* Audio ✅
* Sleep & Wake ✅
* CPU Frequency ✅
* Hand Off/iCloud ✅

## Issues

* Crashed after wake from sleep: enable PowerTimeoutKernelPanic option in config.plist

## BIOS settings

* Load UEFI Defaults
* Advanced > Chipset Configuration > Onboard HD Audio & Onboard HDMI HD Audio: Enabled
* Advanced > USB Configuration > XHCI Hand-off: Enabled
* Advanced > Super IO Configuration > Serial Port: Disabled

* Advanced > CPU Configuration > C States Support: Enabled
* Advanced > CPU Configuration > C States Support > CFG Lock: Disabled

* Security > Security Boot: Disabled
* Boot > CSM: Disabled
