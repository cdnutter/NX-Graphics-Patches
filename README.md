# Nintendo Switch Graphics Patches
### ***Modded Switch Required!***  
60 FPS & Resolution Mods  

**Requirements**
- [sys-clk](https://github.com/retronx-team/sys-clk)
- [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- [Tesla Menu](https://gbatemp.net/threads/tesla-the-nintendo-switch-overlay-menu.557362/) - *Recommended, not required*

**Instructions** 
 
**All-in-One**

0. Install Atmosphere & sys-clk ***properly***
1. Drag and drop all contents *inside* all-in-one folder onto your Switch root directory *(e.g. one with atmosphere, bootloader, switch, etc)*
2. Reboot to CFW.

**Individual Packs**

0. Install Atmosphere & sys-clk ***properly***
1. Drag and drop specified elements into respectable folders. *(e.g. ones with Title IDs inside `/atmosphere/titles` and exe_patches inside `/atmosphere`.
2. Reboot to CFW.

## Credits
- https://github.com/masagrator/NXGraphicsPatches/
- https://gbatemp.net/members/kirby567fan.439698/
- https://gbatemp.net/members/masagrator.467296/
---

# 60 FPS
*Note*: Not all games will have 100% stable 60 FPS, these more-or-less uncap the framerate or produce better framerates altogether.
### Assassin's Creed Rebel Collection
**Source**: https://gbatemp.net/threads/assassins-creed-the-rebel-collection-60-fps-mod.553706/
```
; Assassin’s Creed 4
[010044700DEB0000]
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
handheld_charging_mem=1600

; Assassin’s Creed Rogue
[010044700DEB0001]
handheld_charging_cpu=1785
handheld_charging_gpu=768
handheld_charging_official_gpu=921
handheld_charging_mem=1600
```

### A Hat in Time
**Source**: https://gbatemp.net/threads/a-hat-in-time-60-fps-mod.551579/
```
[010056E00853A000]
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_charging_mem=1600
```

### ABZU
**Source**: https://gbatemp.net/threads/abzu-60-fps-mod.547812/
```
[0100C1300BBC6000]
handheld_charging_cpu=1224
handheld_charging_gpu=768
handheld_charging_mem=1600
```

### Monster Hunter Rise - *(NA)*
**Source**: https://gbatemp.net/threads/monster-hunter-rise-60-fps-mod.585713/
```
[0100B04011742000]
handheld_charging_cpu=1785
handheld_charging_gpu=921
handheld_charging_mem=1600
```

### Monster Hunter Rise - *(JP)*
**Source**: https://gbatemp.net/threads/monster-hunter-rise-60-fps-mod.585713/
```
[0100559011740000]
handheld_charging_cpu=1785
handheld_charging_gpu=921
handheld_charging_mem=1600
```

