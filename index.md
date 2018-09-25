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


#### **This is still WIP, if you feel like you are not finding the answers you are looking for, ask it on our discord server:  **
[https://discord.gg/4x86FfX](https://discord.gg/4x86FfX "https://discord.gg/4x86FfX")

# How to add keybind and alternate keys
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
