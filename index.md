# Welcome to UE4 Advance Menu System Guide

#### How to add keybind and alternate keys
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
