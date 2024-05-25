# Thinkpad-X1-Carbon-Gen8 Hackintosh
- Lenovo Thinkpad x1 Carbon Gen 8
- CPU: 10th Gen Intel(R) Core(TM) i7-10510U 1.8GHz
- RAM: DDR4 2666 16GB
- GPU: Intel® UHD Graphics 630 for 10th Gen Intel® Processors
- LAN: Intel Ethernet I219V10
- Wi-Fi: Intel AX201-D2W
- Sound: ALC285 ID=71
- MacBookPro16,3
- macOS: Monterey
- Working: OpencCore 8.6
# ACPI
- SSD-AWAC.aml
- SSDT-EC-USBX-LAPTOP.aml
- SSDT-PLUG-DRTNIA.aml
- SSDT-PNLF.aml
- SSDT-XOSI.aml
# Drivers
- HfsPlus.efi
- OpenHfsPlus.efi
- OpenRuntime.efi
- ResetNvramEntry.efi
- ToggleSipEntry.efi
- OpenCanopy.efi
# Tools
- CleanNvram.efi
- CFGLock.efi
- VerifyMsrE2.efi
- OpenShell.efi
- ControlMsrE2.efi
# KextS
- Lilu
- VirtualSMC
  + SMCBatteryManager
  + SMCProcessor
  + SMCSuperIO
- WhateverGreen
- AppleALC
- NVMeFix
- USBMap (USBInjectAll)
- CPUFriend
- CPUFriendDataProvider
- HibernationFixup
- BrightnessKeys
- BlueToolFixup
- IntelBluetoothFirmware
- IntelBTPatcher
- itlwm
- IntelMausi
- ECEnabler
- VoodooI2C
- VoodooI2CHID
- VoodooPS2Controller
