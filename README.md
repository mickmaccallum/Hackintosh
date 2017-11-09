# Hackintosh - High Sierra 10.13.1

Assembly instructions for my current Hackintosh build. Here to help anyone who wants to do something similar, or myself in the likely event that I blow this thing up at some point in the future.

# Config

## Build

- Core (Tweaks for compatibility detailed below)
	- [Intel Core i7 6700K 4.00 GHz Unlocked Quad Core Skylake](https://www.amazon.com/gp/product/B012M8LXQW/)
	- [ASUS ROG MAXIMUS VIII HERO ALPHA](https://www.amazon.com/gp/product/B017RI8UYA/)
	- [Ballistix Elite 32GB Kit (8GBx4) DDR4 3000 MT/s](https://www.amazon.com/gp/product/B01H3P9BXG/)
	- [EVGA SuperNOVA 850 P2, 80+ PLATINUM 850W](https://www.amazon.com/gp/product/B010HWDOH6/)
	- [Corsair Crystal Series 460X RGB](https://www.amazon.com/gp/product/B01LA2LB7W/)
	- [NVidia GEFORCE GTX 1080 Ti](https://www.nvidia.com/en-us/geforce/products/10series/geforce-gtx-1080-ti/)
	- [Samsung 950 PRO Series - 512GB PCIe NVMe - M.2 Internal SSD](https://www.amazon.com/gp/product/B01639694M/) (Only used for Windows)
	- [Samsung 850 EVO 500GB 2.5-Inch SATA III Internal SSD](https://www.amazon.com/Samsung-2-5-Inch-Internal-MZ-75E500B-AM/dp/B00OBRE5UE/)
	- [WD Black 5TB Performance Desktop Hard Disk Drive](https://www.amazon.com/gp/product/B013DHNLN4/)
	- [Fenvi 802.11AC Desktop Wifi Card](https://www.amazon.com/gp/product/B01MDLG51U/)
	- [EKWB X240 Complete Dual 120mm Liquid Cooling Kit](https://www.amazon.com/Complete-120mm-Liquid-Cooling-EK-KIT/dp/B00LXIRCAE/)
- Peripherals
	- [Razer DeathAdder Chroma](https://www.amazon.com/gp/product/B00MYTSDU4/) (OOB, config available through [Razor Synapse](https://www.razerzone.com/synapse/))
	- [Apple Wired Keyboard with Numeric Keypad](https://www.amazon.com/Apple-Keyboard-Compatible-v-10-6-8-MB110LL/dp/B005DPF08E/) (OOB)
	- [Apple Magic Trackpad 2](https://www.amazon.com/Apple-Magic-Trackpad-2-MJ2R2LL/dp/B016QO5YWC/) (OOB)
	- [Logitech C922x Pro Stream Webcam](https://www.amazon.com/gp/product/B01LXCDPPK/) (OOB, both camera and microphone)
- Software
	- [Microsoft Windows 10 Pro 64 Bit](https://www.amazon.com/Microsoft-Windows-10-Pro-Bit/dp/B00ZSHDJ4O/)
- Accessories
	- [Hackintosh Stickers](https://www.etsy.com/listing/105566118/hackintosh-apple-skull-logo-custom-mash?ga_order=most_relevant&ga_search_type=all&ga_view_type=gallery&ga_search_query=hackintosh&ref=sr_gallery_1)
	- [NZXT Aer RGB & HUE+](https://www.nzxt.com/products/aer-rgb-hue)
	- [NZXT Aea RGB](https://www.nzxt.com/products/aer-rgb)

## Software

### Applications Used

- Unibeast 8
- Multibeast 10
- KextBeast
- Clover Configurator

### Boot Flags

- `darkwake`
- `dart=0`
- `nvda_drv=1`

### General

- UEFI Boot Mode
- FakeSMC kext
- FakeSMC Plugins kext
- FakeSMC HWMonitor Application kext
- Set SMBIOS system definition to `iMac 17,1` (this is the one with a 6700k)
- 3rd Party USB 3.0 kext
- 7/8/9 Series USB Support kext
- USB increase max port limit kext
- SATA/eSATA/AHCI SATA kexts
- NVidia Graphics Fixup

### Ethernet

- IntelMausiEthernet v2.2.0 kext

### WiFi

- OOB on Fenvi 802.11AC Desktop Wifi Card. Onboard Wi-Fi does not work.

### Bluetooth

OOB on motherboard

### Graphics

- Remove "Inject Nvidia" option
- Install Nvidia web driver [378.10.10.10.20.107](https://images.nvidia.com/mac/pkg/378/WebDriver-378.10.10.10.20.107.pkg) for macOS 10.13.1

Disable "inject Nvidia" to make multiple displays work and remove "0mb" of vram in system report. Requires Nvidia web drivers to be installed first.

### USB

- Enable "Injection" setting
- Enable "Ownership" setting

### Audio

- Enable "Inject" setting "1"
- Install `ALC1150` and `100 Series Audio` kexts

### Clover Drivers

- EmuVariableUefi.efi

### iMessage

https://www.reddit.com/r/hackintosh/comments/2wohwn/getting_imessage_working_on_10102_generating/

![All Done](/images/complete.jpg)


