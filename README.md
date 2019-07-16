# TWRP device tree for Ulefone Armor 6

## About Device

![Ulefone Armor 6](http://ulefone.com/images/armor-series/armor6/armor-6-features-bg-24.jpg)

### Specifications


Component Type | Details
--------------|-------
CPU     | Octa-core (4x2.1 GHz Cortex-A73 & 4x2.0 GHz Cortex-A53) Helio P60
Chipset | MT6771 (12 nm)
GPU     | Mali-G72 MP3
architecture | 64 bit
Memory  | 6 GB RAM
Shipped OS | Android 8.1
Storage | 128 GB DDR4X (expandable storage up to 256GB (VFAT))
Battery | Non-removable Li-Ion 5000mAh battery
Height | 166mm
Width | 75.6mm
Thickness | 13.3mm
Weight | 267.5g (with battery)
Display | 6.2" (16cm) IPS LCD capacitive touchscreen, Notch Screen
Aspect Ratio | 19 : 9
Screen To Body Ratio | ~91.8%
Pixel density | ~402 PPI
Screen resolution | 720 x 1520 pixels
Protection | Corning Gorilla Glass 5, Scratch Resistance, 7 Mohs Scale
Quick charging | Yes, 18W, 9V, 2A
Wireless Charge | Yes, 10W, Qi Standard
Wifi | Yes, IEEE802.11 a/b/g/n/ac, dual-band, WiFi Direct, hotspot 
Bluetooth | 4.2, A2DP, LE
NFC | Yes, Google Pay
GPS | Yes, with A-GPS, GLONASS
USB | USB 2.0, Type-C
Body Build | Front glass, plastic(Polycarbonate) body
Colours | Black, Dynamic Black, Radiant Blue
Network support | Both SIM slots are compatible with 4G, support 4G VoLTE in both slots simultaneously
Card | Triple Slots / dual nano-SIM
SIM | Nano SIM + Nano SIM/TF
Sensors | G/P/L Sensor, Accelerometer, Bubble level, Barometer, Sound Meter, Protractor, Pic hanging, Height Measure, Plumb bob, Pedometer Gyroscope, E-compass, UV Light Detecter, Fingerprint(rear-mounted)


Rear Dual Camera | AI Front Camera | Video
----------------|---------------|-----
16 MP(Interpolated to 21MP)+8 MP(Interpolated to 13MP) | 8 MP (Interpolated to 13MP)
PDAF Fast Focusing | ƒ/1.8 large aperture
f/1.8 Aperture | 1.12μm Pixels
5P Lens | AI Beautification
Nightscape | HDR
Hybrid HDR | AI Beautification
Ultra HD | AI Facial Unlock
Chroma Boost
Portrait Mode
Dual LED Flash

Network | Bands
-------|-----
gsm | B2/3/5/8
WCDA | B1/2/4/5/8
CDMA | BC0/BC1
TDSCDMA | B34/B39
TDD-LTE | B34/38/39/40/41
FDD-LTE | B1/2/3/4/5/7/8/12/17/19/20/28A/28B
GPRS | Available
EDGE | Available
HSPA | Available

**This device tree can be used to build twrp for Ulefone Armor 6**

## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
source build/envsetup.sh
lunch omni_Armor_6-eng
mka recoveryimage
```
