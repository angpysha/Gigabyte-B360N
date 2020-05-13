# System Specifications

![](screenshot.png)

## System Specifications

- **OS:** MacOS Mojave 10.14.6
- **Bootloader:** OpenCore 0.5.7
- **Motherboard:** Gigabyte B360N Wifi
  * Ethernet: 1x Intel I219-V7 Gigabit Ethernet + 1x Intel I211 Gigabit Ethernet
  * Audio Codec: Realtek ALC887 (Layout 1)
  * Wireless: Realtek 8822BE
  
- **CPU:** Intel i5 9400
- **GPU:** Sapphire RX 570 ITX 8GB
- **RAM:** Corsair Vengeance LPX 16GB 2x8GB DDR4 2666Mhz
- **Storage:** Adata XPG SX8200 PRO 512GB M.2 NVMe
- **WiFi & Bluetooth:** BCM94360CS2 + NGFF M.2 Adapter

## BIOS Settings

**Disabled:**
- Fast Boot
- VT-d
- CSM

**Enabled:**
- VT-x
- Above 4G decoding
- Hyper-Threading
- OS type: Windows 8.1/10 UEFI Mode

## Misc
- Patch CFG Lock (MSR Ex02): `setup_var 0x5C1 0x00`

## Guides & Links

- [OpenCore Vanilla Desktop Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)

## Known Issues

- Internal WiFi & Bluetooth are not supported.

## To Dos

- [x] USB Mapping
- [x] Replace internal WiFi > ~~DW1560~~ BCM94360CS2
- [ ] Replace WiFi antenna