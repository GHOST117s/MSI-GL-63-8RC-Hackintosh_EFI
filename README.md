# MSI-GL-63-8RC-Hackintosh_EFI



## Specs




| Name             | Details                                                                |
| ----------------- | ------------------------------------------------------------------ |
|Model|GL63-8RC|
| CPU | Intel Core i5-8300H   |
|RAM  | Samsung 16 GB DDR4 2666 mhz |
| CPU Family |  Coffee Lake  |
| WiFi Chipset |Intel Wireless-AC 9560 160MHz  |
| Audio Codec |  ALC 235  |
| SSD |  SK-Hynix  (500gb) |

##  Whats Working 
Fixed HDMI Output in latest commit

WiFi      ✅

Bluetooth ✅

Sound    ✅

Keyboard ✅

TrackPad  & trackpad buttons ✅

Function Key ✅

Brightness ✅


##  Not Working
* AirDrop
* nvdia 1050 4GB  so Disabled
* How to Check Gpu if On or off  in MSI
* If Led Of power Key is White then Turned Of
* If Red Then Gpu is Powered On

## Bugs
- AirDrop  (showing the iphone but tapping on share nothing happens )
- Closing And Opening  laptop lid  Cause Nvdia Gpu Get Power On (You can check power key led turned red ) And it is the main Problem for battery drain so If you also facing this just Restart Again
- Hibernate error. system wont wake up if goes to sleep you have to manually restart it.

## BIOS Setting 
### Disable 
- Fast Boot
- Secure Boot
- VT-d
### Enable
- Boot Mode UEFI
- SATA Mode: AHCI
- Hyper-Threading

For more about BIOS Follow This Guide For Detailed Info

https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#intel-bios-settings










## Thanks 
- [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/)