
# Advance Menu System Guide for Unreal Engine
You can get the Menu System from the UE4 marketplace, if you haven't already: 
https://www.unrealengine.com/marketplace/advanced-menu-system

Want to test the Menu system? Download the demo version and try it:
https://1drv.ms/u/s!AshlE4zYrQfJ2XFtfLXsdTGDwqmi


------------



Here are some youtube previews:
[https://youtu.be/QhqDYmP0ciU](https://youtu.be/QhqDYmP0ciU "https://youtu.be/QhqDYmP0ciU")

Pause Menu Preview: [https://www.youtube.com/watch?v=vranbs3nfGM](https://www.youtube.com/watch?v=vranbs3nfGM "https://www.youtube.com/watch?v=vranbs3nfGM")

------------


#### This is still WIP, if you feel like you are not finding the answers you are looking for, ask it on our discord server:
[https://discord.gg/4x86FfX](https://discord.gg/4x86FfX "https://discord.gg/4x86FfX")

## How to add keybind and alternate keys
You can just create new mappings for that. do not stack up multiple action keys in a single mapping.
basically **DO NOT DO THIS**:

![](https://cdn.discordapp.com/attachments/442452324988747776/494176222994104330/unknown.png)

instead create a separate mapping:

![](https://cdn.discordapp.com/attachments/442452324988747776/494176383518507010/unknown.png)

for axis mapping, you can stack up multiple inputs in a single mapping, just **DO NOT USE SAME VALUE** for the scale.

![](https://cdn.discordapp.com/attachments/442452324988747776/494176864944914432/unknown.png)

even if you want to have same value just add some fraction value.
also if you want to add more rebindable inputs:

![](https://cdn.discordapp.com/attachments/442452324988747776/494177595282292754/unknown.png)

make sure the `input name` is the same specified in the project input settings.
the axis values should match.
and add the default key so when player resets the keybind it resets to the specified key.


## Why am i getting this message "You will need to add Advance Menu system plugin to enable this functionality"
The Menu system has UI scaling functionality, but due to limitation of blueprint it is distributed as a separate plugin. Download it from here, it is completely free:

[Downlaod the Plugin](https://gum.co/nspP)

## How to enable UI scaling functionality
First download the additional functionality here: [Downlaod the Plugin](https://gum.co/nspP)

Then follow this tutorial: [https://www.youtube.com/watch?v=FECDS9sZf-Q](https://www.youtube.com/watch?v=FECDS9sZf-Q)


## Why can't i see Video on my Menu background after packaging/building the game
This is due to UE4 not packaging the video file with the game. UE4 does not include file with extension other than `.uasset` by default.

You can change this by changing the package settings. Follow this tutorial here:
[https://wiki.unrealengine.com/How_To_Package_Extra_NonUASSET_Files_With_Your_Game](https://wiki.unrealengine.com/How_To_Package_Extra_NonUASSET_Files_With_Your_Game)

## Audio settings don't work after i add my own sound
You need to set audio class in your imported audio files. double click on the sound file. and you can assign a sound class there:

![image](https://cdn.discordapp.com/attachments/442450806760013826/493417445558845440/unknown.png)


You can also use sound cue. create a sound cue from the audio file.

![image](https://cdn.discordapp.com/attachments/442450806760013826/493417839668232192/unknown.png)

then double click the sound cue to open it up and assign sound class there.

![image](https://cdn.discordapp.com/attachments/442450806760013826/493418115355377674/unknown.png)

if you are using sound cue, then make sure when you are playing the audio, you change it to cue not the original audio file:

![image](https://cdn.discordapp.com/attachments/442450806760013826/493418468318904332/unknown.png)
