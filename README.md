--- yum kavo lollypop hub
-- LightTheme
--  DarkTheme
--   GrapeTheme
--  BloodTheme
--  Ocean
--   Midnight
--  Sentinel
--  Synapse

local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = kavoUi.CreateLib("Lollypop Hub V2","Ocean")

--skripts tab
local Skripts = Window:NewTab("Skripts")
local SkriptsSection = Skripts:NewSection("Skript hub by lulaslollipop🍭😋")

SkriptsSection:NewButton("99% fail impossible obby", "purple = ✅, red = ❌, green = ✅, tile broke, or 🔥 ", function()
-- lulas 99 fail memory skript
loadstring(game:HttpGet(('https://pastebin.com/raw/DhLMep63'),true))()
end)

SkriptsSection:NewButton("Heaven", "anti-lag for 99% fail obby", function()
loadstring(game:HttpGet("https://pastebin.com/raw/RW7ZT29m"))()
end)

local SkriptsSection = Skripts:NewSection("Skripts")

SkriptsSection:NewButton("Fly GUI V3", "mobile fly",
function()-- fly gui v3 
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-FLY-GUI-V3-8402"))()
end)

SkriptsSection:NewButton("Infinite Sprint", "no speed limit, inkreases speed",
function()-- fe parkour 
loadstring(game:HttpGet("https://pastebin.com/raw/R5YR13pG"))()
end)

SkriptsSection:NewButton("GodMode", "no death 99% fail only",
function()-- fe brixk toggle press Z 
loadstring(game:HttpGet("https://pastebin.com/raw/6g3h9cDB"))()
end)

SkriptsSection:NewButton("Mobile Keyboard", "why u looking here",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)

SkriptsSection:NewButton("R15 to R6", "only work if u are r15",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua", true))()
end)



-- admin skripts
local Admin = Window:NewTab("Admin")
local AdminSection = Admin:NewSection("Admin Kommands")

AdminSection:NewButton("Infinite Yield", "type the kommand in the kommand bar", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

AdminSection:NewButton("Fates Admin", "default prefix :", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)

local AdminSection = Admin:NewSection("Bonus😁")

AdminSection:NewButton("Nameless Admin", "type ;cmds", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)



-- Fun SKRIPTS
local Fun = Window:NewTab("Fun")
local FunSection = Fun:NewSection("😱🍭")
local FunSection = Fun:NewSection("Anims")

FunSection:NewButton("Lolly Animations", "work r15 and r6", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/yeerma/1/main/the_greatest_script_ever_made'))()
end)

FunSection:NewButton("Energyze Animations", "work r15 and r6", function()loadstring(game:HttpGet(('https://pastebin.com/raw/1p6xnBNf'),true))()
end)

local FunSection = Fun:NewSection("Message Fun")

FunSection:NewButton("Xhat Troll", "type for others", function()
loadstring(game:HttpGet('https://pastebin.com/raw/MBpnp3yS'))()
end)

FunSection:NewButton("Auto Exkuse", "auto msg wen u die", function()
getgenv().dmsgs = {
  deathmessages = {"i was lagging", "that wasnt fair", "bruh thats kap", "i wasnt paying attention", "i was doing something", "my mom kalled me", "that wasnt fair", "wow bro"}
}
--[[
Auto-Exkuse
]]--
loadstring(game:HttpGet("https://raw.githubusercontent.com/goldmoments/auto-excuse/main/Script"))("Auto-Excuse Script | flamespill#7488") 
end)

FunSection:NewButton("Rainbow", "enables xhat bubble and see msg frm far away", function()
--enables bubble chat also

textcolour = Color3.new(0,0,0)

game:GetService("Chat").BubbleChatEnabled = true

coroutine.wrap(function()

    while wait() do

        for i = 0,255,10 do

            textcolour = Color3.new(255/255,i/255,0/255)

            wait()

        end

        for i = 255,0,-10 do

            textcolour = Color3.new(i/255,255/255,0/255)

            wait()

        end

        for i = 0,255,10 do

            textcolour = Color3.new(0/255,255/255,i/255)

            wait()

        end

        for i = 255,0,-10 do

            textcolour = Color3.new(0/255,i/255,255/255)

            wait()

        end

        for i = 0,255,10 do

            textcolour = Color3.new(i/255,0/255,255/255)

            wait()

        end

        for i = 255,0,-10 do

            textcolour = Color3.new(255/255,0/255,i/255)

            wait()

        end

    end

end)()

local settings = {

	}

while wait() do

    pcall(function()

    	game:GetService("Chat"):SetBubbleChatSettings({

            TextColor3 = textcolour,

            -- The amount of time, in seconds, to wait before a bubble fades out.

            BubbleDuration = 20,

            -- The amount of messages to be displayed, before old ones disappear

            -- immediately when a new message comes in.

            MaxBubbles = 25,

            -- Styling for the bubbles. These settings will change various visual aspects.

            BackgroundColor3 = Color3.fromRGB(0, 0, 0),

            TextSize = 20,

            Font = Enum.Font.Ubuntu, --Enum.Font.GothamSemibold

            Transparency = .1,

            CornerRadius = UDim.new(0, 30),

            TailVisible = true,

            Padding = 8, -- in pixels

            MaxWidth = 500, --in pixels

            -- Extra space between the head and the billboard (useful if you want to

            -- leave some space for other character billboard UIs)

            VerticalStudsOffset = 0,

        

            -- Space in pixels between two bubbles

            BubblesSpacing = 3,

        

            -- The distance (from the camera) that bubbles turn into a single bubble

            -- with ellipses (...) to indicate chatter.

            MinimizeDistance = 300,

            -- The max distance (from the camera) that bubbles are shown at

            MaxDistance = 2500,

        })

    end)

end
end)

FunSection:NewButton("SpamHub", "sing songs etx.", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/ColdStep2/Chatdestroyer-Hub-V1/main/Chatdestroyer%20Hub%20V1'),true))()
end)

local FunSection = Fun:NewSection("Humanoid")

FunSection:NewButton("Destroy Body", "yea", function()
loadstring(game:HttpGet("https://pastebin.com/raw/naRUdxrc", true))()
end)

-- tools 
local Tools = Window:NewTab("Tools")
local ToolsSection = Tools:NewSection("Tools")

ToolsSection:NewButton("BTools", "building tools", function()
a = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
a.BinType = 2
b = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
b.BinType = 3
c = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
c.BinType = 4
end)

ToolsSection:NewButton("Super Tools", "kool toools", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/Super%20tools"))()
end)

ToolsSection:NewButton("Tp Tool", "equip and press to tele anywhere", function()
mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Equip to Klixk Tp"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
end)

ToolsSection:NewButton("Tp To Player GUI", "equip and press to tele anywhere", function()
loadstring(game:HttpGet(("https://pastebin.com/raw/YNVbeqPy")))()
end)



-- hubs and gui
local Hub = Window:NewTab("Hubs")
local HubSection = Hub:NewSection("Hubs")

HubSection:NewButton("ASTRAL HUB V3", "a hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/AstralHub/main/Main.lua", true))()
end)

HubSection:NewButton("Harsh Texh v7.4", "lots of skripts", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Beta/main/HarshTech7.4.lua'),true))()
end)

HubSection:NewButton("Skript Loader", "huge GUI", function()
loadstring(game:HttpGet("https://pastebin.com/raw/zzYSdwhk", true))()
end)



-- game skripts
local Games = Window:NewTab("Games")
local GamesSection = Games:NewSection("Games")

GamesSection:NewButton("Find The Markers", "easy tp to random marker", function()loadstring(game:HttpGet('https://pastebin.com/raw/7gu2ztpP'))()
end)

GamesSection:NewButton("50/50 Pixk A Door", "reveals all doors in lime green", function()getgenv().Door = true

while wait() do
    if getgenv().Door == true then
        for i,v in pairs(game.Workspace.Doors:GetChildren()) do
            for i,l in pairs(v:GetChildren()) do
                if l:FindFirstChild("???") then
                    l.BrickColor = BrickColor.new("Lime green")
                end
            end
        end
    end
end
end)

GamesSection:NewButton("KAT GUI", "esp,spam shoot (aimbot💻)", function()--kat gui
loadstring(game:HttpGet("https://pastebin.com/raw/78kG7trR"))()
end)



-- FE SKRIPTS
local Fe = Window:NewTab("FE")
local FeSection = Fe:NewSection("FE Skripts")

FeSection:NewButton("FE Time Reverse", "reverses what u do", function()
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
Library.DefaultColor = Color3.fromRGB(0,255,0)

Library:Notification({
    Text = "provided by lulaslollipop",
    Duration = 4
})

wait (2)

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
Library.DefaultColor = Color3.fromRGB(0,255,0)

Library:Notification({
    Text = "SKRIPT EXEKUTED 🍭🍭🍭🍭",
    Duration = 4
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/L"))()
end)

FeSection:NewButton("FE Portal Gun", "type user first and shoot gun to tp to them", function()
loadstring(game:HttpGet("https://pastebin.com/raw/H9B4aGij"))()
end)

FeSection:NewButton("FE Avatar Kreator", "move your axxessories anywhere", function()
loadstring(game:HttpGet("https://pastebin.com/raw/TTQn3RDk"))()
end)

FeSection:NewButton("FE Kamera Slider", "yeah", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/rouxhaver/scripts-2/main/Camera%20Sliders.lua"))()
end)

FeSection:NewButton("FE Mimik GUI", "kopy users messages", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/0Ben1/fe./2520c121ab919b2b9697ab5c70797dcfdaa5db43/Ohio'))()
end)




-- ovas tabs
local Ovas = Window:NewTab("Others")
local OvasSection = Ovas:NewSection("Others")

OvasSection:NewButton("Universal Spy GUI", "player list gui", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/MichaelScripter/MiniScript/main/Spy gui.lua"))()
end)

OvasSection:NewButton("Universal Aimbot", "simple aimbot skript", function()
-- AIMBOT by lulaslollipop
loadstring(game:HttpGet("https://textbin.net/raw/uv6wy7lbdb"))()
end)

OvasSection:NewButton("noOoOoOoOoooooOoOo", "fling a player by walking into them", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
end)

Section:NewKeybind("Toggle", "toggle", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)