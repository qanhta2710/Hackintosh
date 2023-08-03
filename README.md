# Hackintosh
An EFI for Dell Latitude 3510 i3-10110U Comet Lake with OpenCore
![image](https://github.com/alluka3101/Hackintosh/assets/26887540/e251496e-e0e9-4819-af78-864a752da3f5)

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
| SSD NVMe         | Samsung 970 EVO Plus 1TB           |
| SSD SATA         | Samsung 870 EVO 250GB              |
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
