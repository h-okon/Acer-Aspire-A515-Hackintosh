### WARNING

<sub><sup>
 ###### /** Your warranty may be void.* * I am not responsible for bricked devices, dead SD cards, dead hard drivers or ANY damage and * thermonuclear war, or you getting fired because the calendar app failed. Please * do some research if you have any concerns about files included in this repository* before installing it! YOU are choosing to make these modifications, and if* you point the finger at me for messing up your device, I will laugh at you. If you wish to proceed - you are free to do so! I mean you are on github - you should know what you are doing.*/
  </sub></sup>
  
  



![alt text](https://i.imgur.com/tNUJpOw.png  "Logo")
[click here to view full res image](https://i.imgur.com/zn9kw5U.png)
# 
 # Acer Aspire A515-51G i5-8250U/8GB/MX130 - my daily driver
## <center>is what I picked instead of 12" MacBook</center>
## But why you may ask, well - here are some benchmarks:
![benchmarks](https://i.imgur.com/YJLJFUv.png)
### Hardware used:

![alt text](https://i.imgur.com/gh12k45.png  "specs")


### ⛔️ what is not working:

1. Wi-Fi card (You will need to replace it to the oe that's compatibile - DW1560 will do.)


### WARNING

Remove kexts + kext patches asociated with BCM94352Z(DW1560) if you do not have installed one

### Installation

  

There are many tutorials on how to install OSX on a PC class hardware. However using my Clover you can simply install OS 10.14 or newer on Acer Aspire A515. Make sure to connect USB keyboard and mouse as the I2C bus is supported (yet) during instalation.

  

### Post installation

First things first, if you are using an SSD make sure to enable the TRIM support:

```

$ sudo trimforce enable

```

Install Clover on your hardware, copy EFI to EFI and run those commands:


### reboot and enjoy!
### Credits:

[Clover EFI Bootloader](https://github.com/Clover-EFI-Bootloader/clover)

[Lilu.kext](https://github.com/acidanthera/Lilu/releases)

[VoodooPS2](https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller)

[VoodooI2C](https://github.com/alexandred/VoodooI2C)

[Disable MX130](https://www.tonymacx86.com/threads/guide-disabling-discrete-graphics-in-dual-gpu-laptops.163772/)
