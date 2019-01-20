## !! Make sure to update APFS VFS drivers before proceeding to install !!
https://github.com/acidanthera/AppleSupportPkg/releases




<img src="https://i.imgur.com/n7CC8RU.png" title="hackintosh" alt="hackintosh Project">

# MacBook Pro - but made cheaper.

> Acer Aspire A515-51G


Current running macOS: macOS Mojave 10.14.2 (18C54)
## MAKE SURE TO REMOVE KEXTS ASSOCIATED WITH BCM94325Z UNLESS YOU ARE USING IT.


## Specification:
 - CPU : Intel Core i5 - 8250U 1.6GHz with Turbo Boost up to 3.4GHz (works);
 - GPU : Intel UHD Graphics 620 (MX130 is disabled via DSDT patch);
 - RAM : 8GB of DDR4 2400MHz GoodRam SO-DIMM DDR$ RAM;
 - HDD/SDD : 128GB of Kingston SSD & 1TB Segate Barracuda 5400RPM HDD (SSD for boot drive, HDD only for TimeMachine);
 - Wi-Fi: BCM94325Z m-PCI 
## Known issues:
 - HDMI Audio ( possible sollution: FakePCIID_Intel_HDMI_Audio.kext )
 - Seldom kernel panic on boot related to I2C interface
 - Audio after sleep (not tested)
## Screenshoots:
<img src="https://i.imgur.com/axDujSd.png" title="hackintosh" alt="hackintosh Project">

> HDMI audio & video working:
<img src="https://i.imgur.com/xr3BUMT.png" title="hackintosh" alt="hackintosh Project">
> Major update v1 (13 Jan 2019)

1. updated DSDT
2. disabled the MX130 graphics ( IORegistry does not list RP01 device after applying _OFF from _INI  ACPI Patch
3. battery life improved (+up to 1.5hr)
4. CodecCommander finally fixed
5. wake and sleep issues resolved
6. battery driver replaced
7. deprecated methods removed and updated.
## Credits: 
Huge thanks to <a href = "https://www.tonymacx86.com/members/nortek.1202534/">Nortek</a>, for sharing on tonymacx86 files, which became base for this build.

