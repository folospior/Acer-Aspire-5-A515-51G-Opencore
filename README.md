# Acer Aspire 5 A515-51G Opencore EFI
This repo is made for documenting changes within my Opencore build.

It was **NOT** made to be used as a prebuilt EFI, and should be used for inspiration to creating your own Hackintosh. 

# The guide I was using: https://dortania.github.io/OpenCore-Install-Guide/

I highly suggest you use this one, and this one only. While lengthy, it is best explained and even supports AMD processors.

Specs:
```
> CPU - Intel Core i5-8250U (Kaby Lake-R)

> iGPU - Intel UHD Graphics 620

> dGPU - Nvidia Geforce MX130 - turned off using SSDT-dGPU-Off

> RAM - 8GB 2400MHz Dual-Channel DDR4

> Storage - 240 GB Crucial SATA SSD for data, 480 GB WD Green NVMe SSD for system

> Ethernet - Realtek RTL8111 Ethernet Card 

> Wifi is not working - only ethernet connection. Wifi/Bluetooth card - Qualcomm Atheros QCA9377

> Managed to get Bluetooth to work on my Qualcomm Atheros QCA9377 with BlueToolFixup.kext
```
# Current issues

> Wifi is not working. Probably won't get it to work without a wifi card change.

> After booting up the laptop, the screen is looking funky, as shown in the screenshot below:

![20230219_204139](https://user-images.githubusercontent.com/111700958/220196765-75100f9a-474b-4ccf-8ef8-6b6240164d73.jpg)

> A fix for this is to put the laptop to sleep and wake it up afterwards.

![20230219_204154](https://user-images.githubusercontent.com/111700958/220196892-1b83f151-8af1-4e76-9167-d47a8ee4f4c3.jpg)

# Disclaimers

**I WILL NOT RESPOND TO ANY ISSUES IF YOU DECIDE TO USE IT AS A PREBUILT EFI.**

### If you see any issues with my EFI, I'd love if you help me out. Please don't contact me if you've got an issue though, I am not an expert at all.

*For any help with your **own** EFI, go to: https://www.reddit.com/r/hackintosh or https://discord.com/invite/Wxam8aH*

## Credits:
[Apple](https://apple.com) for macOS.
[Acidanthera](https://github.com/acidanthera) for OpenCore and many Kexts that made this project possible.
Other Kext creators that made this possible as well!
