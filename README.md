Creator: Max
Camera Effects XD is a camera module for roblox!
It lets you create CRAZYY effects and its very easy to adapt.

# USAGE:

For usage you can easily do somthing like

```lua
task.wait(3)

local module = require(game.ReplicatedStorage:WaitForChild('CameraEffectsXD'))
local obj = module.CreateCAMXDobject()

--or any other effect you want!
obj.Nausea = true
--adjust effectiveness n frequency to your liking
obj.Effectiveness.Nausea = 2
obj.Frequency.Nausea = 1.5
--clamp
obj.AutoClamp = true

--Start the effect
obj:Start()
task.wait(10)
--Stop The Effect
obj:Stop()
```

More info on the devforum post:
https://devforum.roblox.com/t/cameraeffectsxdopen-source-wet-vision-nausea-more/4139435
