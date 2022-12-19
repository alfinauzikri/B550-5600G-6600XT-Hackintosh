# RyzenTosh B550/5600G/RX 6600 XT
OpenCore EFI for B550 Chipset Motherboard with AMD Ryzen 5 5600G Processor + Radeon RX 6600 XT Graphics Card.

## Specification

- Motherboard     : MSI B550M-A Pro
- BIOS      : AMI BIOS 7C96v29
- CPU       : AMD Ryzen 5 5600G with Radeon Graphics
- RAM       : 2 x 16GB DDR4 3600Mhz
- Storage   : 500GB SSD + 1TB HDD
- dGPU      : AMD Radeon RX 6600 XT 8 GB
- Wifi/BT : Intel® Dual Band Wireless-AC 8265 + Bluetooth 4.2
- Ethernet  : Realtek RTL8111 Gigabit Ethernet
- Audio     : Realtek ALC892
- Boot Mode : UEFI
- Bootloader : OpenCore 0.8.7
- OS : macOS Ventura 13.1 (Build 22C65) + Windows 11 Pro

## Whats Work?

- QE/CI Graphics of RX 6600 XT + DRM
- CPU Power Management
- Sleep/Wake
- Shutdown and Restart
- All USB Ports
- Ethernet
- Wifi
- Bluetooth
- HDMI
- Audio (Rear & Front)
- TRIM Support for SSD
- Etc

## Tutorial
- From Zero Tutorial : https://dortania.github.io/OpenCore-Install-Guide/
- Creating the USB Installer : https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
- Generating SMBIOS : https://github.com/corpnewt/GenSMBIOS
- USB Fixes : https://dortania.github.io/OpenCore-Post-Install/usb/ and https://github.com/usbtoolbox/tool

Tutorial on "USB Fixes" related to the UTBMap.kext and SSDT-SLEEP.aml files. Please pay close attention to the guidelines that have been provided.

All kinds of errors and kernel panics, beyond my responsibility.

## Results
![Screenshot 2022-12-19 at 23 31 44](https://user-images.githubusercontent.com/14070303/208474954-27f296fe-ea67-4485-9874-0fc14e7dec94.png)

![Screenshot 2022-12-19 at 23 41 17](https://user-images.githubusercontent.com/14070303/208475833-ee64b1c0-48e2-4cca-a662-acef192670d7.png)

![Screenshot 2022-12-19 at 23 43 21](https://user-images.githubusercontent.com/14070303/208476289-1a5a690a-b65e-45a9-963b-a565bee3276d.png)

![Screenshot 2022-12-20 at 00 24 58](https://user-images.githubusercontent.com/14070303/208484200-d7a09d39-5366-41e8-ba68-456b565b1675.png)

![Screenshot 2022-12-19 at 23 44 47](https://user-images.githubusercontent.com/14070303/208476516-b0d11a7c-4832-4868-be55-cb92da6db780.png)
