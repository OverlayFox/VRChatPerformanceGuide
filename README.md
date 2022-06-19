# VRChatPerformanceGuide
## A Guide to help out getting VRChat to work more smoothly and crash less

This Guide is aimed at people with an NVIDIA GPU and we will also recommend some mods to use.

**Very important to note:** VRChat does **not** allow the use of mods, so using them can get you banned from the platform indefinitly, even if those mods only affect your own game and not anybody elses experience
We are not liable for any bans that may happen due to you trying to make the game run more smoothly

This Guide is aimed towards performance not quality. You can change any of these settings to your liking

## NVIDIA Control Panel
Navigate to your task bar and search for the NVIDIA Settings Icon and right click on it.
From here, open the NVIDIA Control Panel

![image](https://user-images.githubusercontent.com/88669300/174494166-8165521d-06a1-4f29-b719-d2df0e234f0d.png)

Once the Window has open you want to navigate to *Manage 3D settings* under *3D Settings*
In there you want to hit the second tab called *Program Settings*
You will find a dropdown menu where you can select a program to edit, you want to select *VRChat* in there.
(If VRChat is not in that list you can simply click the *Add* Button and select it from a longer list or Browse for it and select the *VRChat.exe* which you will find in *C:\Program Files (x86)\Steam\steamapps\common\VRChat*)

![image](https://user-images.githubusercontent.com/88669300/174494897-92bee9dd-996c-4937-a1c7-45f3e46c9c11.png)

Once done you want to change these settings to the following:

```
Antialiasing - FXAA: Off
Antialiasing - Mode: Off
CUDA - GPUs: (select your main GPU here)
Exported pixel types: Colour indexed overlays (8 bpp)
Low Latency Mode: Ultra
Max Frame Rate: 60FPS (you can set this higher if you want more FPS but the more frames you allow, to more extrem the frame drops will be)
OpenGL Rendering GPU: (select your main GPU here)
Optimise for Computer Performance: On
Power management mode: Prefer consistent performance
Texture filtering - Quality: High performance
Threaded optimisation: On
```

Click apply at the bottom right

## General Settings

In VRChat itself you should go to your saftey settings and hide all avatars, even the ones from your friends, and reveal them on a one by one basis.
This will drasticly improve performance and stability but has the biggest impact on your gaming experience

## Mods

**VRChat forbits the use of mods, these are only inteded to be used if everything else fails.**
Currently we will only list them but in the future we will give detailed instructions on how to set them up properly

Advanced Safety:
https://github.com/knah/VRCMods/releases

Ask to Portal:
https://github.com/SleepyVRC/Mods/releases/tag/v2022-05-29

FrameFocus:
https://github.com/MintLily/FrameFocus/releases

Lag Free Screenshots:
https://github.com/knah/VRCMods/releases

Turbones (this one can screw up Physbones so it can cause issues with some models):
https://github.com/knah/VRCMods/releases

TrueShaderAntiCrash:
https://github.com/knah/VRCMods/releases
