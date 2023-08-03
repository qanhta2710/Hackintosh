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
| BootLoader       | OpenCore 0.9.3                     |
| macOS            | Monterey 12.6.7                    |
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
- ✅ Brightness Keys

# Not Working ❌:
- ❌ Microphone (Intel Smart Sound Technology is not supported)
- ❌ AirDrop (Can find devices but cannot connect)
- (?) Handoff (Not test)
# Alternative Microphone: Use an earphone which has mic or just buy an USB microphone
# BIOS Settings:
  # Enable:
  - SATA Mode: AHCI
  - VT-x
  - Hyper-Threading
  - VT-d
  # Disable:
  - Secure Boot
  - Fast Boot: Auto
