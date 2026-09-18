# SKYVR TEMPORARY STORAGE

anyways, until presidentanvil makes another repo for skyvr, use this.

# 19/09/2026

fullbody is broken it seems, atleast for me, though havent seen anyone really talk about fullbody. to be fair, it is a few years old by now, so the method is broken or roblox screwed some stuff up.

the first issue was value of type nil cannot be converted to a number, but this is fixable by adding "limbTransparency = (numberhere)," to the options.

even with that, fullbody is broken, cant move and most hats are just gone, not sure how to fix it since im not exactly good at scripting, especially with stuff like this.


```lua
-- DO NOT RUN THIS IN VR MODE
skyvrversion = '3.0.0'

VR_Model_Customization_GUI = game:GetObjects("rbxassetid://93922799482853")[1]
VR_Model_Customization_GUI.Parent = game.CoreGui

loadstring(game:HttpGet("https://raw.githubusercontent.com/iedatemporarystore/SkyVR_TemporaryStorage/refs/heads/main/VRCustomizationMain.lua"))()
```
