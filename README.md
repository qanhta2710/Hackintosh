# Hackintosh
An EFI for Dell Latitude 3510 i3-10110U Comet Lake with OpenCore
![Screen Shot 2021-08-09 at 17 54 25](https://user-images.githubusercontent.com/26887540/128696055-15f32a4e-9acc-4e9e-946f-fbc0496f7221.png)
![image](https://user-images.githubusercontent.com/26887540/128727253-b863a823-a0eb-46b0-a5cd-226f5e903076.png)

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
| BootLoader       | OpenCore 0.7.3                     |
| macOS            | Big Sur 11.5.1                     |
| Windows          | Windows 11                         |
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
