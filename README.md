# HP-M01-F1033wb-hackintosh-efi-10100-uhd630
Opencore EFI set up for hackintosh to work with Ventura 13.2.1

## Usage:
* Important: Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate a unique device id for your machine, choose `iMac20,1`
* Have fun

## Specs
* Model: [HP M01-F1033wb](https://support.hp.com/us-en/product/hp-desktop-pc-m01-f1000i/32482405/model/35801263/document/c06687602)
* CPU: Intel 10th Gen i3 10100
* Chipset: b460m (BakerMS)
* Ram: 8GB DDR4
* SSD: Bio Star G30-240 240GB (newly installed)
* HDD: 1TB
* Graphics: UHD630

## Software
* Open Core: 0.8.9
* GenSMBios: iMac20,1

## Known Issues
* The original wifi card (RTL8821CE) is not supported, there are three options and the first two options can work with airdrop:
  * [Most Ideal] Replace it with a [M.2 wireless card](https://dortania.github.io/Wireless-Buyers-Guide/types-of-wireless-card/m2.html#supported-cards) 
    * **The space in the model is tight, please pay attention to the size**
  * [Still good] Add a new pice wireless card/adapter
  * [Less ideal] A compatbile usb card
* The motherboard only supports HDMI 1.4a, if you want to connect to a 4k monitor, add a compatible AMD graphics card