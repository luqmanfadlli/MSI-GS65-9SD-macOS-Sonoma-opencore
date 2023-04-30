# Introduction
This is my personal documentation after successfully installing macOS Monterey and Ventura on my MSI GS65 Stealth 9SD and use it as daily driver.

# Machine information
|Parts|Details
|:---:|:---:|
Model | MSI GS65 Stealth 9SD
CPU | Intel® Core™ i7-9750H Processor (2.60 GHz. up to 4.50 GHz. 12M Cache)
Intel Generation | Coffee Lake
RAM | 6GB (2x 8GB) DDR4
iGPU | Intel CoffeeLake-S GT2 [UHD Graphics 630]
dGPU | NVIDIA GeForce GTX1660Ti 6GB (disabled as not supported by macOS)
Display | 15.6-inch FHD (1920×1080), 144Hz 100%sRGB
Wifi | Killer AC Wi-Fi
Bluetooth | Intel
Audio | Realtek ALC1220
SSD0 | ADATA XPG 512GB (purchased additionally, macOS installation and bootloader)
SSD1 | TOSHIBA 512GB (shipped barebone, Windows 11 installation and bootloader)

# macOS information
macOS 13.3.1 Ventura

# Bootloader information
OpenCore: 0.9.1

# What's Working
* Display functions (Color, Brightness, etc)
* Wifi
* Bluetooth
* Trackpad (multitouch and gesture support)
* Keyboard
* USB
* Webcam
* Audio
* Mic
* Sleep/Wake

# Notes
* I highly recommend building your own files by following Dortania's excellent guide. it will help you understand the big picture and how to use my files correctly. After you went through all the guide, you can use my files as an referance. 
* The config.plists in each folder doesn't have any SMBIOS data to avoid any mixups. Please add your own. I used MacBookPro16,4.
* If it somehow failes to boot with all my files, the problem is likely to be the DSDT.aml. DSDT is known to be unique to each devices. You will have to make your own DSDT and fix it with patches. Major patches are Battery and brightness. Take a look at my DSDT to see how I patched them. You can look for tutorials by rehabman in Tonymac.

# Credits
* Dortania
* acidanthera
* Corpnewt
* Rehabman
* Olarila

and many others that I have forgotten to include, sorry.
