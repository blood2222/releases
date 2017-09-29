# Releases
Wallets and Essentials <br><br>
Signatum releases for Windows, Linux, ARM and more.<br>
<br>
Instructions for Linux Qt / Daemon depends.<br>
-----------------------------------------<br>

If you get dependencies errors then it means you are missing one of these: <br>
libssl-dev libdb++-dev libdb-dev libboost-all-dev libqrencode-dev libminiupnpc-dev <br>
Install by sudo apt-get install libssl-dev libdb++-dev libdb-dev libboost-all-dev libqrencode-dev libminiupnpc-dev <br>
<br>

# Notes:

1. Qt based wallets for ARM are not tested <br>
2. DTB for A64 SoC is a WIP and apt upgrade corrupts the bootloader. Stick to the default kernel as the development for this SoC is 
slow and full of bugs.
3. H3 and H5 based SoC boards must be used with a heatsink due to high clock speeds. Expect big CPU throttles wihtout them.

Orange Pi Prime: http://www.orangepi.org/OrangePiPrime/ (H5 SoC based) <br>
Raspberry Pi: https://www.raspberrypi.org/products/raspberry-pi-3-model-b/ (Broadcom arm71 based)<br>
Orange Pi Win Plus: https://www.open-electronics.org/new-a64-quad-core-orange-pi-win-plus/ (A64 Based Soc)<br>
Nano Pi: http://nanopi.io/nanopi-m1.html (H3 SoC based) <br>

Do not forget to chmod +x signatumd after downloading and installing dependencies. 
