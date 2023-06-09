# Flipper Zero 101
**Date:** 05/21/2023

## Debunking Myths
- FlipperZero can not clone financial cards, the information on the card alone contains no financial information in itself. The card simply contains the secrets neccesary to start a connection with the bank's server and this secret changes for every transaction or after a certain amount of time. 

## Custom Firmware vs Official Firmware
### Official Firmware
-	Stability.
-	Easier to use.
-	Mobile app screen mirroring.
-	Long term support. 
### Custom Firmware
-	Bypass regional blocks.
-	Plugins, custom graphics and third-party apps pre-loaded.
-	Can be difficult to install.
-	Stability issues. 
#### RogueMaster
https://github.com/RogueMaster/flipperzero-firmware-wPlugins
#### Unleashed
https://github.com/DarkFlippers/unleashed-firmware

## qFlipper
Download > https://docs.flipperzero.one/qflipper
Desktop app for Flipper Zero, great for screen mirroring to PC, small file transfer, firmware upgrades (official firmware only). 

## File Transfer
For larger file transfers is easier to write the files directly to the MicroSD card.

## AV Exceptions
It’s recommended to add the folder(S) where you will be downloading the Flipper files to your AV’s exception list to avoid files being removed or detected as malicious.  

## Use Cases
### MFA
Flipper Zero can be used as a USB security key (U2F)to sign in into web accounts, you can find websites that support this by visiting https://www.dongleauth.com/  
### Universal Remote Control
If you keep losing the remote for everything at home just keep the Flipper in your pocket and control anything and everything with an IR receiver. 
### Bad USB
FlipperZero can connect to other devices as Human Interface Device (HID) this connection mode allows the Flipper to act as BadUSB. A Bad USB device can change system settings, open backdoors, retrieve data, initiate reverse shells, or do anything that can be achieved with physical access.
- Compatible with Ducky Script
- Payloads > https://shop.hak5.org/blogs/payloads/  
- Hak5 Payload Studio Community Edition > https://payloadstudio.hak5.org/community/ 
- USB Rubber Ducky e-Book > https://shop.hak5.org/collections/e-books/products/usb-rubber-ducky-e-book
### NFC
FlipperZero devices can read, emulate and store NFC cards. It can be use for things like consolidating multiple cards on a single device or detect hidden NFC readers. 
### Wi-Fi Pentesting
The Flipper can be used as a powerful Wi-Fi Pentesting tool by adding the ESP32-S2 Development Board which provides the Flipper Zero with the hardware required for WiFi capabilities. Flashing the Wi-Fi Dev board with the Marauder firmware by Just Call Me Koko gives provides a suite of toosl to use your Wi-Fi pentesting. 
- Flipper Zero WiFi Dev Board with Marauder > https://github.com/justcallmekoko/ESP32Marauder/wiki/flipper-zero
- Easy Flipper Zero Marauder Flash > https://github.com/SkeletonMan03/FZEasyMarauderFlash
#### Create an Inexpensive Router for Testing Wi-Fi Hacking Techniques
Project > https://github.com/martin-ger/esp32_nat_router
HakByte: Build a Hackable Router with a $5 ESP32 > https://www.youtube.com/watch?v=41Lymi6rXA8&t=341s
#### Deauthentication
A Wi-Fi deauthentication attack is a type of denial-of-service attack that targets communication between a user and a Wi-Fi wireless access point. It can be used as standalone attack to disable devices like cameras or smart doorbells or as part of an attempt to crack the password of a wireless network. 
Learn more about Wireless Deauthentication Attacks > https://cybr.com/courses/wireless-deauthentication-attacks/
#### Wi-Fi Password Cracking
FlipperZero can be used to capture the handshake from a wireless connection to then attempt to obtain the network's passphrase. 
- Wireshark > https://www.wireshark.org/download.html
- HashCat > https://hashcat.net/hashcat/
- Handshake Extractor > https://hashcat.net/cap2hashcat/ 
- Rockyou Password Wordlist > https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt
- 74GB Wordlist Released – PrincessPi7.4 > https://h.acker.is/74gb-wordlist-released-princesspi7-4/

## Links
-	Official Docs > https://docs.flipperzero.one/ 
-	Wi-Fi Dev Board Pro > https://github.com/DarkFlippers/unleashed-firmware
-	Repo of all things FlipperZero > https://github.com/UberGuidoZ/Flipper
-	Flipper-IRDB > https://github.com/UberGuidoZ/Flipper-IRDB 
-	DownGit > https://minhaskamal.github.io/DownGit/#/home
-	FlipperZero App Marketplace > https://flipc.org/ 

## YouTube Videos Worth Watching
-	The ULTIMATE Beginners Guide to Flipper Zero!! Get ALL the Files & Apps and Install Custom Firmware! > https://www.youtube.com/watch?v=8izMLBMxsOA
-	Hacking WiFi Passwords with Flipper Zero, Marauder, Wireshark and HashCat! > https://www.youtube.com/watch?v=subLBPJ3IxU
