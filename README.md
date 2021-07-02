# HUANANZHI X99-F8 GAMING

<a href="https://www.paypal.com/donate?hosted_button_id=ASF2H5CU95MUQ">
  <img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/PayPal.png" alt="Donate with PayPal" />
</a>
<a href="https://www.paypal.com/donate?hosted_button_id=ASF2H5CU95MUQ">
  <img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/QR-PayPal.png" alt="Donate with PayPal" />
</a>

* ##### (UEFI Only / Legacy Not Supported)
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

* ##### How Update CX99DE to CX99DE firmware.
* ##### ⚠️ If you have another BIOS - USE programmer device !!!
* ##### ⚠️ If you ignore instruction, and updated any firmware with use software method, then please do not create error messages, read carefully the instructions.
* ##### ⚠️ In some cases, it is required to reset the Power Good signal (Due to the lack of standardization on the part of the motherboard manufacturer).
![How Update CX99DE25 to CX99DE28](CX99DE26.png)

## CX99DE28 BIOS for HUANANZHI X99-F8 GAMING Motherboard 01/15/2021
## CX99DE27 BIOS for HUANANZHI X99-F8 GAMING Motherboard 11/25/2020
## CX99DE26 BIOS for HUANANZHI X99-F8 GAMING Motherboard 10/10/2020
## CX99DE25 BIOS for HUANANZHI X99-F8 GAMING Motherboard 07/25/2020
  
![CX99DE25 BIOS for HUANANZHI X99-F8 GAMING Motherboard 07/25/2020](MAIN.PNG)
![Realtek UIEFI UNDI Driver](UNDI.png)
![Intel XMP Configuration](MEMORY.png)
![Boot option](BOOT.png)
![PC Health Status](PM.png)
![Save & Exit](SAVE.png)

  Builder: iEngineer

  Manufacturer Bug Fixed, Latest updates, set FSB 100MHz

  Update:
1) ME Firmware (latest) version 9.1.45.3000 (5MiB).
2) EFI/OROM for RSTe SATA(Port 0-3)/sSATA(Port 4-7) firmware up to 5.5.5.1005 ((latest) Full I/O speed).
3) CPU microcode (latest).
4) AMI NVMe firmware (latest).
5) LAN BOOT ROM.
6) EFI Realtek UNDI PCIe GbE Family Controller Driver (2.054, 06/30/2020).
7) DMI Data.

  Deleted:
1) All trash (Unrelated to Huananzhi X99-F8).

  Added:
1) EFI Shell version 2.40.

  Looked:
MBEx, Cipher Transport Layer TLS (CVE-2017-5689 & CVE-2018-3616), PTT, NFC, RPAT, AMT.

  Changes:
1) Enable DUAL/QUAD SPI for Winbond 25Q128FVSG & 25Q128JVSQ.
2) Changes Master Acces from Debug/Manufacturing to Production.
3) Increased BBBS up to 1MiB.
4) WCOD ID 0x0082 TAYLOR.
5) Permanently disabled Intel AMT.
6) Permanently disabled Intel ME Network Service.
7) Hidden BIOS items that do not control.

  How to update Firmware:
1) Burn the Firmware with programmer device. (e.g. EZP-2019)
2) Clear CMOS.
3) After restart go to the BIOS setting & use 'Restore Default' / 'F10' / 'Enter'
4) Configure RAM timings & enjoy.

Addon: 7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS
![Belarus Edition](BELARUS-EDITION.png)

  How to install:
1) Open BIOS file in UEFITool
2) Find (Ctrl+F) GUID 7BB28B99-61BB-11D5-9A5D-0090273FC14D then select (Ctrl+R) Replace as is (choise new downloaded  7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS file).
3) File (Ctrl+S) Save image file.
