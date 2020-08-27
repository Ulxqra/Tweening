
Heres how to tween position in ROBLOX Lua:
local object = script.Parent
object.Position = Udim2.new(1,0,0,0)

object:TweenPosition(0,0,0,0, Enum.EasingDirection.InOut, Enum.EasingStyle.Bounce, 2)
