# Flashlight for Doom VR

![Flashlight for Doom VR](https://i.imgflip.com/24egfa.gif)

A Spotlight based flashlight mod to use with Doom in VR. Unlike the other flashlight mods out there, this flashlight actually follows your tracked controller rather than head movements. It's quite tricky in GZDoom engine since the engine doesn't seem to provide the weapon offsets/angle/pitch so I had to figure out some hacky way to track the controller offset/angle/pitch. I'm not really happy about the sphaghetti codes but hey if it works, it works.

To download the VR Flashlight mod click the download button below:

[![Download Now](https://raster.shields.io/github/downloads/iAmErmac/VR-Flashlight/total)](https://github.com/iAmErmac/VR-Flashlight/releases/latest)

[<img src="https://cdn.ko-fi.com/cdn/kofi2.png?v=2" height="36" alt="Buy me a Cofee!">](https://ko-fi.com/ermac)

## Features
* You can actually hold a flashlight at hand
* While holding the flashlight, use attack button to turn it on/off
* 3D and Voxel model available for the flashlight
* Optional battery capacity and battery indicator right on the Flashlight model itself
* Option to attach flashlight on all your weapons (works universally)
* Quick flashlight toggle available to switch back and forth between your weapon and flashlight or to toggle on/off when it's weapon mounted

## Known Issues
* The flashlight is a bit glitchy at times, like if you are too close to a wall/floor/ceiling the spotlight may jump around because of the nature of the tracking method.
* If the flashlight itself or flashlight mounted weapon clips with other object or wall the spotlight may disappear
* The spotlight becomes tiny when too close to wall/floor/ceiling. To partially fix that I implemented a secondary dynamic light to illuminate area surrounding the spotlight. Sometimes the spotlight and the secondary dynamic light may appear separated depending on the wall/object/corner etc.

## Installation

Make sure to load the VR Flashlight mod after any weapon mod. The Flashlight will be added into the Slot 0 by default.

### GZDoom VR (PC-VR)

Latest GZDoom VR: https://github.com/hh79/gz3doom/releases

To install:

    Extract GZDoom-VR to a folder.
    Copy original doom wads into the folder.
    Copy this mod into the folder.
    Run with gzdoomvr.exe -iwad doom2.wad -file YOUR_FAVORITE_WEAPON_MOD LATEST_FLASHLIGHT_MOD
  
OR use DoomRunner: https://github.com/Youda008/DoomRunner/releases/ to load mods with GZDoom

### QuestZDoom (Oculus Quest)

Official QuestZDoom: https://github.com/DrBeef/QuestZDoom/releases/latest
Unofficial QuestZDoom (For more bugfixes and updates): https://github.com/emawind84/QuestZDoom/releases/latest

QuestZDoom launcher: https://github.com/baggyg/QuestZDoomLauncher/releases/latest

To install:

    Copy this mod into /sdcard/QuestZDoom/mods/
    Load QuestZDoom Launcher. select this mods after a VR weapon mod

## Recommended mods to combine with:

* [DarkDoomZ:](https://github.com/caligari87/darkdoomz/releases/latest)
  - DarkDoomZ can be used to make any Doom level darker by reducing the light levels across all sectors in the map. Use options from DarkDoomZ Settings to adjust the effect as you desire. DarkDoomZ includes it's own head/shoulder mounted flashlight but its not necessary to use it (or you can use both the headmounted and weapon mounted flashlight if you find that convenient)
  
* [Aliens: Eradication:](https://github.com/iAmErmac/Aliens-Eradication-VR-addon)
  - This is a perfect mod to use the flashlight with since it loads any doom map with a very dark environment. Aliens Eradication has it's own head/shoulder mounted flashlight and you can use both if you want to (though it's recommended to use only one)

## Credits

* SuaveSteve (Steve's Flashlight) - base ZScript code for the flashlight
* mshahen - "Flashlight On/Off Clicks" (freesound.org, 271109, modified) CC BY 3.0
* Cherno - for SimSun shader

## 3D Model credits

* Flashlight 3D model - https://sketchfab.com/3d-models/flashlight-for-fps-3612d1eace2f4d1ba9fbd800350e3c74
* Flashlight voxel model converted from 3D model by Ermac
* All 3D models and model textures edited and modified by Ermac
