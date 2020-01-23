# TWRP device tree for Ulefone Armor 7

## About Device

![Ulefone Armor 7](https://www.ulefiles.com/pc/en/images/products/armor-series/armor7/features/Armor-7-PC-01-en_01.jpg)

### Specifications


Component Type | Details
--------------|-------
CPU     | Octa-core (2x2.2 GHz Cortex-A75 & 6x2.0 GHz Cortex-A55)
Chipset | Mediatek MT6779 Helio P90 (12 nm)
GPU     | PowerVR GM9446
architecture | 64 bit
Memory  | 8GB RAM
Shipped OS | Android 9.0
Storage | 128GB
Battery | Non-removable Li-Po 5500 mAh battery
Height | 165.9mm
Width | 81.0 mm 
Thickness | 13.6mm
Weight | 290 g
Display | 6.3 inches IPS LCD capacitive touchscreen
Aspect Ratio | 19.5:9
Screen To Body Ratio | ~72.5%
Pixel density | ~409 PPI
Screen resolution | 1080 x 2340 pixels
Quick charging | Fast battery charging 15W
Wireless Charge | Fast wireless charging 10W
Wifi | Wi-Fi 802.11 a/b/g/n/ac, dual-band, Wi-Fi Direct, hotspot
Bluetooth | 5.0, A2DP, LE
NFC | Yes
GPS | Yes, with A-GPS, GLONASS, GALILEO, BDS
USB | 2.0, Type-C 1.0 reversible connector, USB On-The-Go
Body Build | Drop-to-concrete resistance from up to 1.2 m, MIL-STD-810G compliant
Colours | Black
SIM | Nano SIM + Nano SIM/TF
Sensors | Fingerprint (side-mounted), accelerometer, gyro, proximity, compass, heart rate, baroceptor, coulombmeter

**This device tree can be used to build twrp for Ulefone Armor 7**

## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
source build/envsetup.sh
lunch omni_Armor_7-eng
mka recoveryimage
```
