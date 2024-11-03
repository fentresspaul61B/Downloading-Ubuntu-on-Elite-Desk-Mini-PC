# Downloading-Ubuntu-on-Elite-Desk-Mini-PC
In this project, I walk through the steps in order to use Ubuntu Linux on the Elite Desk 800 G3 Mini PC. 

## What to Order
### 1. Elite Desk 800 G3 
https://www.amazon.com/dp/B08177R8PL?ref=ppx_yo2ov_dt_b_fed_asin_title 

I order the refurbished version of this machine off of amazon for a little over $100. 

### 2. Basic DisplayPort to HDMI Cable
https://www.amazon.com/dp/B015OW3M1W?ref=ppx_yo2ov_dt_b_fed_asin_title

In order to connect to my existing monitor, I purchased this cable, as the visual inputs on this machine use a DisplayPort input rather than an HDMI. 

### 3. Flash Drive: >= 16G
https://www.amazon.com/dp/B01MCY4L2R?ref=ppx_yo2ov_dt_b_fed_asin_title
I ordered a pack of basic flash drives which were 16GB. The most recent Ubuntu should not take up more than 8G, so these should be sufficient. 

### 4. Adapters: (Not Required)
I bought a few different adapters just incase, which included USB_C to USB, and USB to USB-C. 
https://www.amazon.com/dp/B07CVX3516?ref=ppx_yo2ov_dt_b_fed_asin_title
https://www.amazon.com/dp/B0BJ8YQ2LM?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1

# Installation Steps
## Downloading Ubuntu onto Flash Drive
Followed the steps from this video:
https://www.youtube.com/watch?v=870NY3CoHnc

1. Navigate to https://ubuntu.com/download/desktop to download the OS
2. Download the latest version, which as of writing this (10/31/24) is 24.04.1 LTS
3. Navigate to https://etcher.balena.io/ which is a SD card flasher app, which allows users to create USB installation media from bootable ISOs 
4. Select "Download" and then pick your current OS (not the OS of the Elite Desk G3 800, but your other machine). For me, this is MacOS, ARM. Select download again next to your OS
5. Plug in your USB flash drive
6. Navigate to your file explorer and open the recently downloaded etcher app
7. Drag it into your application (or follow other steps relevant to windows installation)
8. Navigate to application and open the new app. 
9. Select "Flash from file"
10. Find your recently downloaded ubuntu-desktop file, and select it
11. Next click on "Select target" and find your flash drive. Mine is named "PNY USB 2.0 FD Media". Select it
12. Now hit the button "Flash!"
13. Enter your PW if required 
14. Wait a few minutes as the download happens
15. When installation is complete, eject it from your machine. 

## Installing Ubuntu from USB to Elite-Desk G3 800 Mini 

1. Plug your mini PC into the power source
2. Connect your mouse, keyboard and monitor
3. Plug in the USB with the downloaded Ubuntu OS
4. Turn on the machine
5. Immediately after turning on the machine, start hitting the escape key, in order to make sure the machine does not auto launch into windows. If it does launch windows, restart the computer and try this again.
6. There will a number of options shown in the boot from menu, now select the one for your USB
7. Hit "Try or Install Ubuntu" If you pause at this step it will start automatically
8. Now go through the steps, and choose the APPs you want. I just went with the default installation
9.  Restart the machine once the download is complete
10. The machine will prompt "Please remove installation device and press enter"
11. Login and you are good to go with Ubuntu!


# Sources
- https://www.youtube.com/watch?v=870NY3CoHnc