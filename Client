local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
OrionLib:MakeNotification({
	Name = "Loading UI...",
	Content = "Client is loading",
	Image = "rbxassetid://4483345998",
	Time = 3
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]
local Window = OrionLib:MakeWindow({Name = "Client", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Tab1 = Window:MakeTab({
	Name = "Game Scripts",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Tab2 = Window:MakeTab({
	Name = "Fun Stuff",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Tab3 = Window:MakeTab({
	Name = "Others",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

Tab:AddParagraph("Welcome To Client","The Best Undetected Natural Disaster Survival Script.")
local Section = Tab1:AddSection({
	Name = "Teleports"
})

--[[
Name = <string> - The name of the section.
]]
Tab1:AddButton({
	Name = "Map",
	Callback = function()
     game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-108, 49, 0)
	end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab1:AddButton({
	Name = "Tower",
	Callback = function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-264, 196, 288)
	end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
local Section = Tab1:AddSection({
	Name = "Others"
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab1:AddToggle({
	Name = "Walk On Water",
	Default = false,
	Callback = function(Value)
		if (Value) == false then do game.Workspace.WaterLevel.CanCollide = false
				game.Workspace.WaterLevel.Size = Vector3.new(10, 1, 10)
			end
		end
		if (Value) == true then do game.Workspace.WaterLevel.CanCollide = true
				game.Workspace.WaterLevel.Size = Vector3.new(1000, 1, 1000)
			end
		end
	end    
})

--[[
Name = <string> - The name of the toggle.
Default = <bool> - The default value of the toggle.
Callback = <function> - The function of the toggle.
]]
Tab1:AddButton({
	Name = "Remove Ads",
	Callback = function()
      		game:GetService("Workspace").BillboardAd:Destroy()
game:GetService("Workspace").ForwardPortal:Destroy()
game:GetService("Workspace").ReturnPortal:Destroy()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab1:AddButton({
	Name = "Remove Sandstorm GUI",
	Callback = function()
      		game.Players.LocalPlayer.PlayerGui.SandStormGui:destroy()
  	end    
})
Tab1:AddButton({
	Name = "Remove Blizzard GUI",
	Callback = function()
      		game.Players.LocalPlayer.PlayerGui.BlizzardGui:destroy()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
	Name = "Copy Discord Invite",
	Callback = function()
      		setclipboard("https://discord.gg/ZHTqjN3mS6")
OrionLib:MakeNotification({
	Name = "Copied To Clipboard",
	Content = "Discord Invite Is Copied To Your Clipboard, Paste it in any Browser To Join.",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab1:AddButton({
	Name = "Launch Land Rocket",
	Callback = function()
      		fireclickdetector(game:GetService("Workspace").Structure["Launch Land"]["SPACESHIP!!"].Shuttle.IgnitionButton.ClickDetector)
fireclickdetector(game:GetService("Workspace").Structure["Launch Land"].RocketStand.ConsoleLower.ReleaseButtonLower.ClickDetector)
fireclickdetector(game:GetService("Workspace").Structure["Launch Land"].RocketStand.ConsoleUpper.ReleaseButtonUpper.ClickDetector)
fireclickdetector(game:GetService("Workspace").Structure["Launch Land"].LoadingTower.Console.ReleaseEntryBridge.ClickDetector)

  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
local Section = Tab2:AddSection({
	Name = "AutoFarm"
})

--[[
Name = <string> - The name of the section.
]]
Tab2:AddButton({
	Name = "Enable",
	Callback = function()
local runService = game:GetService("RunService")
event = runService.RenderStepped:Connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-264, 195, 288)
end)
if game.Players.LocalPlayer.Character.FallDamageScript then
game.Players.LocalPlayer.Character.FallDamageScript:Destroy()
end
end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab2:AddButton({
	Name = "Disable",
	Callback = function()
      		event:Disconnect()
end
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
local Section = Tab2:AddSection({
	Name = "Player"
})

--[[
Name = <string> - The name of the section.
]]
Tab2:AddSlider({
	Name = "WalkSpeed",
	Min = 0,
	Max = 250,
	Default = 16,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "WalkSpeed",
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
	end    
})

--[[
Name = <string> - The name of the slider.
Min = <number> - The minimal value of the slider.
Max = <number> - The maxium value of the slider.
Increment = <number> - How much the slider will change value when dragging.
Default = <number> - The default value of the slider.
ValueName = <string> - The text after the value number.
Callback = <function> - The function of the slider.
]]
Tab2:AddSlider({
	Name = "JumpPowers",
	Min = 0,
	Max = 550,
	Default = 16,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "JumpPowers",
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Value)
	end    
})

--[[
Name = <string> - The name of the slider.
Min = <number> - The minimal value of the slider.
Max = <number> - The maxium value of the slider.
Increment = <number> - How much the slider will change value when dragging.
Default = <number> - The default value of the slider.
ValueName = <string> - The text after the value number.
Callback = <function> - The function of the slider.
]]
Tab2:AddSlider({
	Name = "Gravity",
	Min = 0,
	Max = 196,
	Default = 196,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "Gravity",
	Callback = function(Value)
		game.Workspace.Gravity = (Value)
	end    
})

--[[
Name = <string> - The name of the slider.
Min = <number> - The minimal value of the slider.
Max = <number> - The maxium value of the slider.
Increment = <number> - How much the slider will change value when dragging.
Default = <number> - The default value of the slider.
ValueName = <string> - The text after the value number.
Callback = <function> - The function of the slider.
]]
Tab2:AddSlider({
	Name = "HipHeight",
	Min = 0,
	Max = 50,
	Default = game.Players.LocalPlayer.Character.Humanoid.HipHeight,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "HipHeight",
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.HipHeight = (Value)
	end    
})

--[[
Name = <string> - The name of the slider.
Min = <number> - The minimal value of the slider.
Max = <number> - The maxium value of the slider.
Increment = <number> - How much the slider will change value when dragging.
Default = <number> - The default value of the slider.
ValueName = <string> - The text after the value number.
Callback = <function> - The function of the slider.
]]

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
local Section = Tab3:AddSection({
	Name = "Admins"
})

--[[
Name = <string> - The name of the section.
]]
Tab3:AddButton({
	Name = "Infinite Yield",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/RobloxHackingProject/HPHub/main/IYNotByMe.lua"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab3:AddButton({
	Name = "Client Yield (NOT DONE)",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/wuhaz/scripts/main/myadmin.lua", true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab3:AddButton({
	Name = "Dash Admin",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/wuhaz/scripts/main/real.lua", true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
