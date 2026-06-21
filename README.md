# SKYVR TEMPORARY STORAGE
shoutout to https://github.com/396abc/skyvr for archiving.

anyways, until presidentanvil makes another repo for skyvr, use this. i think i did replace all the loadstrings, but if i didnt i'll fix it as soon as i can.

```lua
-- DO NOT RUN THIS IN VR MODE
skyvrversion = '3.0.0'

VR_Model_Customization_GUI = game:GetObjects("rbxassetid://93922799482853")[1]
VR_Model_Customization_GUI.Parent = game.CoreGui

loadstring(game:HttpGet("https://raw.githubusercontent.com/iedatemporarystore/SkyVR_TemporaryStorage/refs/heads/main/VRCustomizationMain.lua"))()
```
