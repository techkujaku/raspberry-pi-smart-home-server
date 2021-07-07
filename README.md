# Raspberry Pi Smart Home Server
Self hosted server running on a raspberry pi 4 featuring Home Assistant, Open Media Vault (OMV) and several applications deployed using docker (Portainer)

This project is probably overdone by many people but what i see out to do here is to provide a practical working solution that you use at home. My server has been running for several months now prior to the release of this tutorial and i have been adding more applications to it since. This tutorial will serve as the first of many in a series of how my smart home server is setup while also showcasing the many applications running on it.  

# Parts List
* Raspberry Pi 4 (4GB) -
* SD Card and sd card reader
* Kingston A400 M.2 Sata SSD
* <a href="https://my.cytron.io/p-argon1-md2-case-expansion-for-sata-storage"> Argon One Case  </a>
* <a href="https://my.cytron.io/Argon40/p-18w-5v-3p5a-usb-c-power-adapter-uk"> Argon40 18W 5V 3.5A USB-C Power Adapter </a>
  

# Tutorial Overview
* Pi Setup
* Hardware Assembly
* Pi Configuration
* SD card to SSD migration and boot from USB (Optional)
* OMV Setup
* Portainer Setup
* Home Assistant Setup


# Pi Setup
First, download <a href="{https://www.raspberrypi.org/software/operating-systems/">Raspberry Pi OS Lite image</a>
![image](https://user-images.githubusercontent.com/87014174/124711455-aedbd980-df30-11eb-83df-baaebe0f3b44.png)

You won't need desktop versions because most of the time you will be using Secure Shell (SSH) and a browser with the 

Next download <a href="https://www.balena.io/etcher/">Etcher</a>
Connect the SD card reader and SD card to your pc. Open Etcher and select the downloaded OS Lite image. Next select the drive which represents your SD card. You can easily identify it based on the file size of the SD card. CLick on Flash and Wait.

Once it has completed, we'll need to enable SSH on the pi. Safely remove the sd card and reinsert it. Open the folder and create a blank file and name it ssh. Make sure there are no file extensions such as .txt
Safely remove the SD and insert it into the pi.

I prefer using LAN connetion due to speed and stability so connect your pi to the router and boot it up. Log into your router and find the IP address of the pi



# Hardware Assembly

# Pi Configuration

# SD card to SSD migration and boot from USB (Optional)

# OMV Setup

# Portainer Setup

# Home Assistant Setup

# Wrap up and future projects


