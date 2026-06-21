# i'm going to modify the scripts so you'll be able to use SkyVR via this repo
shoutout to https://github.com/396abc/skyvr for archiving

```lua
-- DO NOT RUN THIS IN VR MODE
skyvrversion = '3.0.0'

VR_Model_Customization_GUI = game:GetObjects("rbxassetid://93922799482853")[1]
VR_Model_Customization_GUI.Parent = game.CoreGui

loadstring(game:HttpGet("https://raw.githubusercontent.com/presidentanvil/skyvr/main/VRCustomizationMain.lua"))()
```
