# CUSTOM UEFI FIRMWARE FOR HUANANZHI X99-F8 GAMING
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I1D2IBH)

## RELEASES
* ##### Release CX99DE28 01/15/2021
* ##### Release CX99DE27 11/25/2020
* ##### Release CX99DE26 10/10/2020
* ##### Release CX99DE25 07/25/2020

<div align="left">
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-F8/releases">
        <img src="https://img.shields.io/github/downloads/BIOS-iEngineer/HUANANZHI-X99-F8/total.svg?color=silver&style=for-the-badge&logo=appveyor" alt="downloads"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-F8/releases/latest">
        <img src="https://img.shields.io/github/release/BIOS-iEngineer/HUANANZHI-X99-F8.svg?color=silver&style=for-the-badge&logo=appveyor" alt="latest version"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-F8/blob/master/License">
        <img src="https://img.shields.io/github/license/BIOS-iEngineer/HUANANZHI-X99-F8.svg?style=for-the-badge&logo=appveyor" alt="license"/>
    </a>
</div>

## CREDITS
**Builder: iEngineer**

## BEFORE YOU PROCEED
* ##### ⚠️ UEFI Only / Legacy Not Supported
* ##### ⚠️ If you have factory stock firmware - _YOU MUST USE A PROGRAMMER DEVICE!_ (e.g. EZP-2019 or CH341A) [Instruction CH341A](https://www.miyconst.com/Blog/View/2086/ch341a-minimal-usage-guide-how-to-read-and-write-a-motherboard-bios)
* ##### ⚠️ If you ignored the warning above and flashed your BIOS using firmware update software, please don't create issues, read the instructions carefully and get a programmer device as stated!
* ##### ⚠️ In some cases, it is required to clear CMOS data, for that, you must unplug all power cables to the motherboard and remove the CMOS battery. This is due to the lack of standardization of chinese motherboard manufacturers.

## FIRMWARE FEATURES

### Updated

* Manufacturer bug fixes
* Latest updates
* Set FSB to 100 MHz
* ME firmware to v9.1.45.3000 (5MiB)
* EFI/OROM for RSTe SATA(Port 0-3)/sSATA(Port 4-7) to v5.5.5.1005 (_Full I/O speed_)
* CPU microcode
* AMI NVMe firmware
* LAN BOOT ROM
* EFI Realtek UNDI PCIe GbE Family Controller Driver v2.054 (06/30/2020)
* DMI Data

### Deleted   
* Deleted all trash (unrelated to Huananzhi X99-F8)

### Added
* EFI Shell v2.40

### Looked
* MBEx
* Cipher Transport Layer TLS (CVE-2017-5689 & CVE-2018-3616)
* PTT
* NFC
* RPAT
* AMT

### Changed
* Enable DUAL/QUAD SPI for Winbond 25Q128FVSG & 25Q128JVSQ
* Changed Master Acces from Debug/Manufacturing to Production
* Increased BBBS up to 1MiB
* WCOD ID 0x0082 TAYLOR
* Permanently disabled Intel AMT
* Permanently disabled Intel ME Network Service
* Hidden BIOS settings that are not available on the motherborad

## HOW TO UPDATE THE FIRMWARE
##### ⚠️ If you have factory stock firmware - _YOU MUST USE A PROGRAMMER DEVICE!_ (e.g. EZP-2019 or CH341A)

1. Burn the firmware with a programmer device. (e.g. EZP-2019 or CH341A)
2. Clear CMOS by plugging motherboard power cables and removing the CMOS battery for a few seconds then plug again.
3. After restart load setup default by entering the BIOS setting and then **Restore Defaults -> F10 -> Enter**
4. Configure RAM timings and other settings and enjoy!

## CHANGE FIRMWARE SPLASH SCREEN
![Belarus Edition](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/BELARUS-EDITION.png)

[Download splash screen 7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS](https://github.com/mgscreativa/HUANANZHI-X99-F8/raw/master/7BB28B99-61BB-11D5-9A5D-0090273FC14D.ffs)

### How to install
1) Open BIOS file in UEFITool
2) Find (Ctrl+F) GUID 7BB28B99-61BB-11D5-9A5D-0090273FC14D then select (Ctrl+R) Replace as is (select the downloaded fle 7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS)
3) File (Ctrl+S) Save image file

## UPGRADE FROM CUSTOM FIRMWARE TO CUSTOM FIRMWARE NEW VERSION

![How Update CX99DE25 to CX99DE28](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/CX99DE26.png)

## SCREENSHOTS

![CX99DE25 BIOS for HUANANZHI X99-F8 GAMING Motherboard 07/25/2020](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/MAIN.PNG)
![Realtek UIEFI UNDI Driver](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/UNDI.png)
![Intel XMP Configuration](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/MEMORY.png)
![Boot option](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/BOOT.png)
![PC Health Status](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/PM.png)
![Save & Exit](https://raw.githubusercontent.com/mgscreativa/HUANANZHI-X99-F8/master/SAVE.png)
