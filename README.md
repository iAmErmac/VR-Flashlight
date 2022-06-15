# Flashlight for Doom VR

![Flashlight for Doom VR](https://i.imgflip.com/6ji2r3.gif)

A Spotlight based flashlight mod to use with Doom in VR. Unlike the other flashlight mods out there, this flashlight actually follows your tracked controller rather than head movements. Requires the updated GZDoom build that expose controller position/angle/pitch/roll data into ZScript.

To download the VR Flashlight mod click the download button below:

[![Download Now](https://raster.shields.io/github/downloads/iAmErmac/VR-Flashlight/total)](https://github.com/iAmErmac/VR-Flashlight/releases/latest)

[<img src="https://cdn.ko-fi.com/cdn/kofi2.png?v=2" height="36" alt="Buy me a Cofee!">](https://ko-fi.com/ermac)

## Features
* You can actually hold a flashlight at hand
* While holding the flashlight, use attack button to turn it on/off
* 3D and Voxel model available for the flashlight
* Optional battery capacity and battery indicator right on the Flashlight model itself
* Option to attach flashlight on all your weapons (works universally)
* Quick flashlight toggle to switch back and forth between your weapon and flashlight or to toggle on/off when flashlight is weapon mounted
* Auto flip flashligh while having a tactical hold (Harris Hold)
* Agitate monsters focused in the light (you can turn this off in option)
* You can use flashlight as a basic melee weapon (can hit monsters by 6dof controller movement)

![Flashlight Melee Attack](https://i.imgflip.com/6jr48f.gif)

## Known Issues
* The flashlight is a bit glitchy at times, like if you are too close to a wall/floor/ceiling the spotlight may jump around because of the nature of the tracking method.
* If the flashlight itself or flashlight mounted weapon clips with other object or wall the spotlight may disappear
* Sometimes the spotlight and the bounce light (dynamic light) may appear separated depending on the wall/object/corner etc. Turn off bounced light from option to fix that

## Installation

Make sure to load the VR Flashlight mod after any weapon mod. The Flashlight will be added into the Slot 0 by default.

### GZDoom VR (PC-VR)

Latest GZDoom VR: https://github.com/hh79/gz3doom/releases/latest
Latest GZDoom VR DUal Wield version: https://github.com/iAmErmac/gzdoomvr/releases/latest

To install:

    Extract GZDoom-VR to a folder.
    Copy original doom wads into the folder.
    Copy this mod into the folder.
    Run with gzdoomvr.exe -iwad doom2.wad -file YOUR_FAVORITE_WEAPON_MOD LATEST_FLASHLIGHT_MOD
  
OR use DoomRunner: https://github.com/Youda008/DoomRunner/releases/latest to load mods with GZDoom

### QuestZDoom (Oculus Quest)

Official QuestZDoom: https://github.com/DrBeef/QuestZDoom/releases/latest
Unofficial QuestZDoom (For more bugfixes and updates): https://github.com/emawind84/QuestZDoom/releases/latest
Latest QuestZDoom Dual Wield version: https://github.com/emawind84/QuestZDoom/releases/tag/qzd3.88-r5e

QuestZDoom launcher: https://github.com/baggyg/QuestZDoomLauncher/releases/latest

To install:

    Copy this mod into /sdcard/QuestZDoom/mods/
    Load QuestZDoom Launcher. select this mods after a VR weapon mod

## Recommended mods to combine with:

* [DarkDoomZ:](https://github.com/caligari87/darkdoomz/releases/latest)
  - DarkDoomZ can be used to make any Doom level darker by reducing the light levels across all sectors in the map. Use options from DarkDoomZ Settings to adjust the effect as you desire. DarkDoomZ has it's own head/shoulder mounted flashlight and you can use both if you want to (though it's recommended to use only one)
  
* [Aliens: Eradication:](https://github.com/iAmErmac/Aliens-Eradication-VR-addon)
  - This is a perfect mod to use the flashlight with since it loads any doom map with a very dark environment. Aliens Eradication has it's own head/shoulder mounted flashlight and you can use both if you want to (though it's recommended to use only one)

## Credits

* SuaveSteve (Steve's Flashlight) - base ZScript code for the flashlight
* mshahen - "Flashlight On/Off Clicks" (freesound.org, 271109, modified) CC BY 3.0
* Cherno - for SimSun shader
* Ermac - Flashlight mod scripting and model conversion

## 3D Model credits

* Flashlight 3D model - https://sketchfab.com/3d-models/tactical-flashlight-dfb9ec2ec4f846438eab24f32ec8c656
* Flashlight voxel model converted from 3D model by Ermac
* All 3D models and model textures edited and modified by Ermac
