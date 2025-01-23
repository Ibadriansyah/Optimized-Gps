# Global Optimized GPS File Replacer


# Attention
This is the result of a fork, with no strange intentions, just adding gps.conf for Indonesia


- [Global Optimized GPS File Replacer](#global-optimized-gps-file-replacer)
  - [How it works?](#how-it-works)
  - [Requirements](#requirements)
  - [Instructions](#instructions)
  - [Changelog](#changelog)
      - [Version 5.0](#version-50)
      - [Version 4.0](#version-40)
      - [Version 3.0](#version-30)
      - [Version 2.1](#version-21)
      - [Version 2.0](#version-20)
      - [Version 1.0](#version-10)
  - [Reference](#reference)

This module provides an improved GPS functionality with a better and faster accuracy location reference.

## How it works?
The stock android **_gps.conf_** file found in *"/system/etc/gps.conf"* or *"/system/vendor/etc/gps.conf"* is replaced with a new one correctly edited for a better improvement and faster satellite signals fix/lock.
This file is responsible for the correct GPS operation and functionality.
The default file found in most ROMs is very wrong and has a lot of bad information and settings for the correct operation and functionality of the GPS and A-GPS.

## Requirements
- A device with Qualcomm Snapdragon chipset based.
- Rooted with Magisk and Magisk Manager indeed installed.

## Instructions
__It's Magisk install-able, don't install it by TWRP but with Magisk instead!__

0. [Download](https://github.com/skyrocketingHong/OptmizedGPSConf/releases/latest/download/OptmizedGPSConf.zip)
1. Go to Magisk Manager **_Modules_** section.
2. Click on **_+_** yellow button and search/find for this **_"optimizedgpsconf.zip"_** file and long press on it.
3. Select open and after installed then reboot your device.
4. After rebooted your device, make sure your location settings is setup on mode **_Device only_**.
5. Skirt outdoors, can be in the yard of your house or anywhere else with a line of sight to the sky and stay in that outdoor place.
6. Download some Compass app on Google Play Store *(I recommend the **Compass Steel 3D**)* and then calibrate the compass.
7. Download **_GPS Locker_** app on Google Play Store and open the app and wait for the first time fix/lock. *This is necessary and essential because the app will recognize some GPS satellites signals for the very first time.*

## Changelog

#### Version 5.0
- Use gps.conf from Xiaomi 14 Ultra (HyperOS 1.0.8.0.UNACNXM)
- Update README.md
- Add [release package](https://github.com/skyrocketingHong/OptmizedGPSConf/releases/latest/download/OptmizedGPSConf.zip)

#### Version 4.0
- Use gps.conf of MIUI 13
- Update README.md
- Add [release package](https://github.com/skyrocketingHong/OptmizedGPSConf/releases/latest/download/OptmizedGPSConf.zip)

#### Version 3.0
- Use gps.conf of MIUI 12
- Adapt to Magisk 20.4+

#### Version 2.1
- Template 1500 -> 17000.

#### Version 2.0
- ~~Last update and final version.~~ *Now it works fine for both Android Nougat & Oreo ROMs and is correctly replacing the gps.conf file in corresponding directory path.*

#### Version 1.0
- Initial release

## Reference
- [Module XDA Xiaomi MI 5 Forum Thread](https://forum.xda-developers.com/mi-5/how-to/step-step-definitive-gps-solution-global-t3695769)
- [JonasCardoso/optmizedgpsconf](https://github.com/JonasCardoso/optmizedgpsconf)
#Optimized-Gps
