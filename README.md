# Config

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

- Remove “Inject Nvidia” option
- Install Nvidia web driver `367.15.10.35f01` for macOS 10.12.3

Disable “inject Nvidia” to make multiple displays work and remove “0mb” of vram in system report. Requires Nvidia web drivers to be installed first.

### USB

- Enable “Injection” setting
- Enable “Ownership” setting

### Audio

- Enable “Inject” setting “1”
- Install `ALC1150` and `100 Series Audio` kexts

### iMessage

https://www.reddit.com/r/hackintosh/comments/525dsb/getting_imessage_working_on_el_capitan_and_sierra/
