local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Lumber gui", "Sentinel")
-- LOCAL PLAYER 
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")


PlayerSection:NewSlider("Walk speed", "makes u walk more fast", 500, 16, function(s) -- 500 (MaxValue) | 16 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Jumppower", "makes u jump more high", 350, 50, function(s) -- 350 (MaxValue) | 50 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

PlayerSection:NewButton("God Mode", "God Mode", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/god-mode-/main/README.md'))()
end)

PlayerSection:NewButton("fly", "fly", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/BBgANpmH'))()
end)

--TP
local Tp = Window:NewTab("Tp")
local TpSection = Tp:NewSection("Tp")

TpSection:NewButton("Tp to Frost Wood", "go to Frost Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1489.247, 447.275, 3298.598)
end)

TpSection:NewButton("Tp to palm wood", "go to palm wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2624.676, 3.125, -29.149)
end)


TpSection:NewButton("tp to Cavecrawler Wood", "go to Cavecrawler Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3364.518, -214.718, 494.73)
end)

TpSection:NewButton("tp to Gold Wood", "go to The Gold Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1055.272, -2.875, -885.696)
end)

TpSection:NewButton("tp to Swamp Wood", "go to The Swamp Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1025.859, 133.626, -1175.548)
end)

TpSection:NewButton("tp to Lava Wood", "go to The Lava Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1595.384, 626.025, 1053.488)
end)

TpSection:NewButton("Tp to End Time Wood", "go to End Time Wood", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-41.259, -212.6, -1351.794)
end)

TpSection:NewButton("tp to land store", "go to The land store", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(268.097, 4.225, -98.357)
end)

TpSection:NewButton("tp to woodrus", "go to The woodrus", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(251.219, 6.83, 57.381)
end)

TpSection:NewButton("tp to Boxed Cars", "go to Boxed cars", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(510.255, 4.69, -1488.946)
end)

TpSection:NewButton("tp to FurnitureStore", "go to FurnitureStore", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(491.1, 3.5, -1690.1)
end)

TpSection:NewButton("tp to ShackShop", "go to The ShackShop", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(249.599, 8.168, -2539.08)
end)

--WOOD
local Wood = Window:NewTab("Wood")
local WoodSection = Wood:NewSection("Wood")

WoodSection:NewButton("bring wood", "bring wood", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/bring-wood/main/README.md'))()
end)


--DUPE
local Dupe = Window:NewTab("Dupe")
local DupeSection = Dupe:NewSection("Dupe")

DupeSection:NewButton("Money dupe", "this well dupe your money", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/coming-soon/main/README.md'))()
end)

DupeSection:NewButton("Axe dupe", "this well dupe your Axes", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/coming-soon/main/README.md'))()
end)

--ESP
local Esp = Window:NewTab("Esp")
local EspSection = Esp:NewSection("Esp")

EspSection:NewButton("Player ESP", "Player ESP", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/esp-for-lumber-/main/README.md'))()
end)

EspSection:NewButton("Wood ESP", "Wood ESP", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/coming-soon/main/README.md'))()
end)
