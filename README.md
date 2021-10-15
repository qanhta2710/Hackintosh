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
- ✅ Audio (Using AppleALC) 
- ✅ F1 & F2 & F3 Sound Key 
- ✅ F4 Play/Pause Key 
- ✅ F10 Printscreen Key 
- ✅ USB 3.0 & 3.1 (Not sure about Thunderbolt) 
- ✅ Ethernet, Wi-fi, Bluetooth 
- ✅ iGPU 
- ✅ Battery (Using Kexts) 
- ✅ Ethernet 
# Not Working ❌:
- ❌ Microphone (Since Intel Smart Sound Technology is not supported)
- ❌ AirDrop 
- ❌ F6 & F7 Brightness Key 
# Alternative Microphone:
I use my iPhone as an alternative microphone through USB connect and it's working perfectly
![Screen Shot 2021-08-09 at 18 09 41](https://user-images.githubusercontent.com/26887540/128697598-d0143706-7fd3-4896-9206-d2ed9e6657ff.png)
# Alternative Brightness Keys:
I use Karabiner to remap the brightness keys but it doesn't work anymore on Windows 11 
![Screen Shot 2021-08-09 at 22 42 33](https://user-images.githubusercontent.com/26887540/128734185-62d2ba51-dbdb-4c98-b52c-1078bd71fcf0.png)
# ❗IMPORTANT:
❗ I'm not responsible for any problems that occur. The decision is up to you
# Notices:
- You should build your own EFI because each computer is different
# BIOS Settings:
  # Enable:
  - TPM 2.0
  - SATA Mode: AHCI
  - VT-x
  - Hyper-Threading
  # Disable:
  - VT-d
  - Secure Boot
  - Fast Boot: Thorough
