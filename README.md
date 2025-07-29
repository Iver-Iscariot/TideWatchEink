# TideWatchEink
E-ink display version of my tidal water wrist watch

## Status:
I have sadly not had time to work on this since summer '24.

I have managed to correctly power and write to the e-ink display using an external ESP-32 dev-board. My discrete esp-32 didn't have the necesarry pins for the default pin assignement, so i need to figure out what pins can be used on my breakout board.

I have managed to fetch API tidal data from kartverket.no, and display it on the e-ink screen.
 &nbsp; 
 
 &nbsp; 
 
 &nbsp; 
 
<img width="250" height="255" alt="image" src="https://github.com/user-attachments/assets/1dfecb87-7006-45a5-bfdb-9c95a9ad75ae" />

The previous itteration of the project using an OLED screen, and an atmega328 as the MCU. It consumed to much power, my program used 100% of the storage and i had to manually upload tidal data over usb, hence the switch to the ESP-32

I used a ESP32-S3-WROOM-1 module, the N16R8 version from this aliexpress listing: 
https://www.aliexpress.com/item/1005004538586491.html
