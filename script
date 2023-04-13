-the hardest script ever made

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("shitty hasx cheat v1.00 | Rust#0911", "BloodTheme")

--Tabs

local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")

local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")
--Buttons, sliders and toggle shit

MainSection:NewButton("Get All Coins", "made by the goat yougonnashutup, i couldn't figure it out", function()
    if lplr.Character:FindFirstChild("HumanoidRootPart") then 
    local oldpos = lplr.Character.HumanoidRootPart.Position 
        for i,v in pairs(game:GetService("Workspace").GameObjects:GetChildren()) do 
              lplr.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position) 
            task.wait(0.1)
        end
    lplr.Character.HumanoidRootPart.CFrame = CFrame.new(oldpos)
    
end 
end)

PlayerSection:NewSlider("Walkspeed", "make urself sped", 75, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Jump Height", "make urself high asf", 270, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
