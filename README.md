# Hackintosh
An EFI for Dell Latitude 3510 i3-10110U Comet Lake with OpenCore
![image](https://github.com/qanhta2710/Hackintosh/assets/26887540/cac8af28-e2d3-4c1e-b604-567d34bb0a8b)


# System Information:
| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i3 10110U CML                |
| iGPU             | Intel Graphics UHD                 |
| Audio            | Realtek ALC236                     |
| Ram              | 16 GB 2667 MHz DDR4                |
| Wifi             | Intel(R) Wi-Fi 6 AX201 160MHz      |
| Bluetooth        | Intel(R) Wireless Bluetooth(R)     |
| Ethernet         | Realtek PCIe GbE Family Controller |
| SSD NVMe         | Samsung 970 EVO Plus 1TB           |
| SSD SATA         | Samsung 870 EVO 250GB              |
| SMBIOS           | MacBookPro 16,1                    |
| BootLoader       | OpenCore 0.9.8                     |
| macOS            | Ventura 13.6.4                     |
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
- ✅ Brightness Keys

# Not Working ❌:
- ❌ Microphone (Intel Smart Sound Technology is not supported)
- ❌ AirDrop
- (?) Handoff (Not test)
# BIOS Settings:
  # Enable:
  - SATA Mode: AHCI
  - VT-x
  - Hyper-Threading
  - VT-d
  - TPM 2.0
  - Secure Boot: Tutorial https://github.com/perez987/OpenCore-and-UEFI-Secure-Boot
  # Disable:
  - Fast Boot: Auto
