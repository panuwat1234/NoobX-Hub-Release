local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Noobx Hub", "BloodTheme")
local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("-Teleport-")
Section:NewButton("Lobby", "Tp", function()
    print("Clicked")    
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-155.97119140625, 239.67654418945312, 113.08960723876953)}):Play()
end)
Section:NewButton("Run Quest", "Teleport quest", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-249.39117431640625, 239.479736328125, 427.82073974609375)}):Play()
end)
Section:NewButton("Gk Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(46.72754669189453, 239.77964782714844, -289.8209228515625)}):Play()
end)
Section:NewButton("Dribble Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-870.6663208007812, 256.85455322265625, -252.27044677734375)}):Play()
end)
Section:NewButton("Power Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(487.0538024902344, 706.873779296875, 30.567270278930664)}):Play()
end)

local Tab = Window:NewTab("Cheat")
local Section = Tab:NewSection("Regen Energy")
Section:NewButton("Click Dog", "Regen", function()
    print("Clicked")
game:GetService("Players").LocalPlayer.Character.TPGaining.Get:FireServer()
end)
local Section = Tab:NewSection("Semi-click red(Increase Power Kick)")
Section:NewButton("Click Cat", "For fw", function()
    print("Clicked")
 pairs(game:GetService("Players").LocalPlayer.PlayerGui.HissaPower:GetDescendants()) 
            v:IsA("RemoteEvent") 
                v:FireServer()
end)
Section:NewLabel("Big Hitbox")
Section:NewToggle("Turn it", "Big hitbox", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
local InfiniteJumpEnabled = true game:GetService("UserInputService").JumpRequest:connect(function() if InfiniteJumpEnabled then game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") end end)
game.Players.LocalPlayer.UserId = "2205774994"
_G.HeadSize = 25 _G.Disabled = true game:GetService('RunService').RenderStepped:connect(function() if _G.Disabled then for i,v in next, game:GetService('Players'):GetPlayers() do if v.Name ~= game:GetService('Players').LocalPlayer.Name then pcall(function() v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize) v.Character.HumanoidRootPart.Transparency = 0.7 v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue") v.Character.HumanoidRootPart.Material = "Neon" v.Character.HumanoidRootPart.CanCollide = false end) end end end end)
end)












