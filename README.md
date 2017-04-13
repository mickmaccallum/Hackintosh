# Config

## Hardware

- [Intel Core i7 6700K 4.00 GHz Unlocked Quad Core Skylake](https://www.amazon.com/gp/product/B012M8LXQW/)
- [ASUS ROG MAXIMUS VIII HERO ALPHA](https://www.amazon.com/gp/product/B017RI8UYA/)
- [Ballistix Elite 32GB Kit (8GBx4) DDR4 3000 MT/s](https://www.amazon.com/gp/product/B01H3P9BXG/)
- [EVGA SuperNOVA 850 P2, 80+ PLATINUM 850W](https://www.amazon.com/gp/product/B010HWDOH6/)
- [EKWB X240 Complete Dual 120mm Liquid Cooling Kit](https://www.amazon.com/Complete-120mm-Liquid-Cooling-EK-KIT/dp/B00LXIRCAE/)
- [Corsair Crystal Series 460X RGB](https://www.amazon.com/gp/product/B01LA2LB7W/)
- [EVGA GeForce GTX 980 Ti 6GB FTW](https://www.amazon.com/gp/product/B014PXHC6M/)
- [Razer DeathAdder Chroma](https://www.amazon.com/gp/product/B00MYTSDU4/)
- [Apple Wired Keyboard with Numeric Keypad](https://www.amazon.com/Apple-Keyboard-Compatible-v-10-6-8-MB110LL/dp/B005DPF08E/)
- [Fenvi 802.11AC Desktop Wifi Card](https://www.amazon.com/gp/product/B01MDLG51U/)
- [Logitech C922x Pro Stream Webcam](https://www.amazon.com/gp/product/B01LXCDPPK/)
- [Samsung 950 PRO Series - 512GB PCIe NVMe - M.2 Internal SSD](https://www.amazon.com/gp/product/B01639694M/)
- [WD Black 5TB Performance Desktop Hard Disk Drive](https://www.amazon.com/gp/product/B013DHNLN4/)
- [Microsoft Windows 10 Pro 64 Bit](https://www.amazon.com/Microsoft-Windows-10-Pro-Bit/dp/B00ZSHDJ4O/)

## Software

### Applications Used

- Unibeast
- Multibeast
- KextBeast
- Clover Configurator

### Boot Flags

- `darkwake=0`
- `dart=0`
- `nvda_drv=1`

### General

- UEFI Boot Mode
- FakeSMC v6.21-311 kext
- FakeSMC Plugins v6.21-311 kext
- FakeSMC HWMonitor Application v6.21-311 kext
- SSDT options, enable Sandy Bridge i5/i7 Overclocked
- Set SMBIOS system definition to `MacPro6,1`
- 3rd Party USB 3.0 kext
- 7/8/9 Series USB Support kext
- USB increase max port limit kext
- SATA/eSATA/AHCI SATA kexts

### Ethernet

- IntelMausiEthernet v2.2.0 kext

### Bluetooth

OOB

### Graphics

- Remove "Inject Nvidia" option
- Install Nvidia web driver `367.15.10.35f01` for macOS 10.12.3

Disable "inject Nvidia" to make multiple displays work and remove "0mb" of vram in system report. Requires Nvidia web drivers to be installed first.

### USB

- Enable "Injection" setting
- Enable "Ownership" setting

### Audio

- Enable "Inject" setting "1"
- Install `ALC1150` and `100 Series Audio` kexts

### iMessage

https://www.reddit.com/r/hackintosh/comments/525dsb/getting_imessage_working_on_el_capitan_and_sierra/
