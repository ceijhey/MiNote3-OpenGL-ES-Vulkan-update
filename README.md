# MiNote3-OpenGL-ES-Vulkan-update
This is a TWRP flashable zip for Xiaomi Mi Note 3 intended to update your OpenGL ES and Vulkan drivers.
I am testing this on Android 9, Xiaomi.eu MIUI 12 beta channel but it should work on MIUI 12/11/10 based Android 9 and AOSP Android 10/9.
This zip is based on @ceijhey's magisk module named GV-VKRVxxx

## Disclaimer
Use at your own risk. I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

## Features
- OpenGL ES 3.2 V@454.0
- Vulkan 1.1.128
- Some build.prop patches (rendering tweaks, GPU acceleration, force launcher into memory, smoother video streaming and tweak media)

## Installation
0. Back up /system/ files (or do a full backup)
1. Flash your new ROM or update (optional)
2. Flash this zip
3. Reboot to system
4. Enjoy

## Screenshots
<img src="/Screenshots/phone_info.jpg" width="200" title="Mi Note 3 device info"> <img src="/Screenshots/opengl_es_version.jpg" width="200" title="OpenGL ES"> <img src="/Screenshots/vulkan_api.jpg" width="200" title="Vulkan">

## Revert
If something doesn't work, restore your backup or dirty flash (flash over) your new ROM/update again.
After each flash, the original build.prop is backed up as build.prop.GL_VK_bak under /system/

## Custom build.prop options
If you want to add some more options in your build.prop, you can add them in "/tmp/update-build.prop", and they will be included in your buid.prop after flashing it.

## Credits
All thanks go to ceijhey. You can get in contact with him at [Mi Note 3 channel in Telegram](https://t.me/s/minote3channel).
Buid.prop edit code: To edit the build.prop, the code from [this XDA post](https://forum.xda-developers.com/showpost.php?p=19093919&postcount=20) by unCoRrUpTeD was used.

## I want more
Join the Telegram channel of [Mi Note 3](https://t.me/s/minote3channel).
For a Mi Note 3 Google Camera TWRP fix, have a look [here](https://github.com/GreatApo/MiNote3-Camera2API-fix).
