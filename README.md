# Hackintosh
An EFI for Dell Latitude 3510 i3-10110U Comet Lake with OpenCore
![image](https://user-images.githubusercontent.com/26887540/196015003-1ac9f2d4-6389-4c7c-b81a-7cb75f7a5cb8.png)
# System Information:
| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i3 10110U CML                |
| iGPU             | Intel Graphics UHD                 |
| Audio            | Realtek ALC236                     |
| Ram              | 4 GB 2667 MHz DDR4                 |
| Wifi             | Intel(R) Wi-Fi 6 AX201 160MHz      |
| Bluetooth        | Intel(R) Wireless Bluetooth(R)     |
| Ethernet         | Realtek PCIe GbE Family Controller |
| SSD NVMe         | PNY CS1031 256GB SSD               |
| SMBIOS           | MacBookPro 16,1                    |
| BootLoader       | OpenCore_NO_ACPI 0.8.5             |
| macOS            | Monterey 12.6                      |
| Windows          | Windows 10                         |
# Working ✅:
- ✅ Touchpad 
- ✅ Shutdown/Restart/Sleep 
- ✅ Internal Camera 
- ✅ Audio 
- ✅ All USB Ports 
- ✅ Ethernet, Wi-fi, Bluetooth 
- ✅ iGPU 
- ✅ Battery 
- ✅ BrightnessKeys

# Not Working ❌:
- ❌ Microphone (Intel Smart Sound Technology is not supported)
- ❌ AirDrop  
# Alternative Microphone:
I use my iPhone as an alternative microphone through USB connect and it's working perfectly
![Screen Shot 2021-08-09 at 18 09 41](https://user-images.githubusercontent.com/26887540/128697598-d0143706-7fd3-4896-9206-d2ed9e6657ff.png)
# BIOS Settings:
  # Enable:
  - SATA Mode: AHCI
  - VT-x
  - Hyper-Threading
  - VT-d
  # Disable:
  - TPM 2.0
  - Secure Boot
  - Fast Boot: Auto
