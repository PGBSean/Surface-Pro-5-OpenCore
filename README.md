# Surface-Pro-5-OpenCore

This repo lets you download the EFI for the Surface Pro 5 lineup.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

**Thank you for 100 views of this repository!**

## Credits
+ Thanks to @MrHomebrew for the creation of the Surface Pro 5's EFI. Even though your EFI is really messed up, but I managed to fixed it.
+ Thanks to @Xiashangning for the BigSurface kext. This makes the type cover, touch, stylus works flawlessly on this machine!
> Post-install procedure is required.

## Screenshot
<img width="1368" alt="image" src="https://github.com/PGBSean/Surface-Pro-5-OpenCore/assets/97381104/6b836385-6148-4c61-88de-3711c060a834">



## This EFI contains:
+ Mapped graphics & USB
+ Monthly bug fixes from OpenCore and associates
+ Android tethering support (HoRNDiS)

## Installation:
1. Download the latest EFI via [Releases](https://github.com/PGBSean/Surface-Pro-5-OpenCore/releases)
2. Prepare USB via [OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#making-the-installer) **ONLY MOVE `com.apple.recovery.boot` FOLDER**
3. Move downloaded EFI folder to USB
4. Boot via USB and install MacOS

## Bugs
+ No camera support
> This is to be expected since BigSurface does not implement camera support yet.

+ No Windows Hello support
> bffr when did macOS support face id

+ No Wi-Fi & Bluetooth support

+ [?] No iServices
> Not yet tested, but might be fixed in the next release ASAP.


## Tested versions
+ macOS Catalina
+ macOS Big Sur
+ macOS Monterey
+ macOS Ventura
+ macOS Sonoma

