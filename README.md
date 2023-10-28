-- Gui to Lua LOLLYPOPHUB
-- Version: 6.9
-- Instanxes:
loadstring(game:HttpGet("https://pastebin.com/raw/uNb6892M",true))()
--loadstring(gameLoaded:true)--
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
Library.DefaultColor = Color3.fromRGB(50,205,50)

Library:Notification({
  Text = "LOLLYPOP HUB V6.9🍭😋🍭😋",
  Duration = 9
})
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
Library.DefaultColor = Color3.fromRGB(50,205,50)

Library:Notification({
  Text = "almost every skript in this joint",
  Duration = 8.5
})
--bloodball.Endnotif
game:GetService("StarterGui"):SetCore("SendNotification",{ 	
Title = "made by:",  	
Text = "lulaslollipop🍭",
  Icon = "rbxthumb://type=Asset&id=11425468695=150&h=150",
  Duration = 6
})


local Library = loadstring(game:HttpGet("https://pastecode.dev/raw/MsVeci5gQG/kavomobileUi",true))()
local Window = Library.CreateLib("Lollypop Hub🍭 | V6.9","BloodTheme")

---//yum lollypop hub\\--
-- LightTheme
-- DarkTheme
-- GrapeTheme
-- BloodTheme
-- Ocean
-- Midnight
-- Sentinel
-- Synapse
-- Serpent(new)
--tools1134,skripts35,game1443

--skripts tab
local Skripts = Window:NewTab("Skripts")
local SkriptsSection = Skripts:NewSection("Skript hub by lulaslollipop🍭😋")
SkriptsSection:NewDropdown("FREE UGC SKRIPTS:","updates and add-ons to the skript will be here", {"Last Updated: 10/27/2023", "Version: 6.9", "3+ hubs added", "added Brixk Admin, Vortex admin", "gui fixes"}, function(currentOption)
  print(currentOption)
end)

SkriptsSection:NewLabel("Welkome" ..plr.Name)

-- SKRIPTS BUTTONS
SkriptsSection:NewButton("99% fail impossible obby memory skript", "purple = ✅, red = ❌, green = ✅, tile broke, or 🔥 ", function()
-- lulas 99 fail memory skript
loadstring(game:HttpGet(('https://pastebin.com/raw/DhLMep63'),true))()
end)
-- toggle antimythikal
SkriptsSection:NewToggle("Anti-Sit (99% fail mythikals)", "kinda good but i prefer using godmode", function(state)
  if state then
      local RunService = game:GetService("RunService")
function antiSit()
if game.Players.LocalPlayer.Character.Humanoid:GetState() == Enum.HumanoidStateType.Seated then 
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
end
RunService:BindToRenderStep("tempBinding", 1000, antiSit)

game:GetService("StarterGui"):SetCore("SendNotification",{ 	
Title = "Anti-Mythikal✅",  	
Text = "u will auto stand",

Duration = 3
})
  else
      local RunService = game:GetService("RunService")
function antiSit()
if game.Players.LocalPlayer.Character.Humanoid:GetState() == Enum.HumanoidStateType.Seated then 
game.Players.LocalPlayer.Character.Humanoid.Sit = true
end
end
RunService:BindToRenderStep("tempBinding", 1000, antiSit)

game:GetService("StarterGui"):SetCore("SendNotification",{ 	
Title = "Anti-Mythikal❌",  	
Text = "off",

Duration = 3
})
  end
end)
--end toggle antimythikal

SkriptsSection:NewButton("Heaven Map (99% fail)", "reduxes lag too", function()
loadstring(game:HttpGet("https://pastebin.com/raw/RW7ZT29m"))()
end)

-- SkriptsSection:NewButton("Vietnam notifier🚨📢", "will send u a notif if viet joins", function()
-- -- be notified wen viet joins
-- loadstring(game:HttpGet("https://pastebin.com/raw/C96cg2xG"))()
-- end)

SkriptsSection:NewButton("Kokushibo notifier🚨📢", "will notify u if kokushibo joins",
function()-- kokushibo notifier
loadstring(game:HttpGet("https://pastebin.com/raw/1hnL2uEj"))()
end)
SkriptsSection:NewButton("Anti-Ban (read how to enable)", "anti xhat logger", function()loadstring(game:HttpGet("https://raw.githubusercontent.com/rrixh/antixhatlogger/main/lulaslollipop",true))()
end)

SkriptsSection:NewButton("ANTI-AFK", "no afk",
function()local vu = game:GetService("VirtualUser")
  game:GetService("Players").LocalPlayer.Idled:connect(function()
     vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
     wait(1)
     vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
  end)
  --end anti afk 
      local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
  Library.DefaultColor = Color3.fromRGB(50,205,50)

  Library:Notification({
      Text = "now they kant stop u frm sleeping😴",
      Duration = 5.5
  })
end)

SkriptsSection:NewButton("Fluxus Koral remake", "kredits Anya",
function()
    --fluxus remake(kredits to Anya)
loadstring(game:HttpGet("https://pastecode.dev/raw/DhToGLHKE9/fluxusExekutor_lulaslollipopAnya",true))()
end)

local SkriptsSection = Skripts:NewSection("Skripts")

--infjump.Konnekt
SkriptsSection:NewToggle("Infinite jump", "no jump limit", function(toggled)
  if toggled then
      getgenv().InfJump = true
      spawn(function()
          while getgenv().InfJump == true do
              game:GetService("UserInputService").JumpRequest:connect(function()
                  if getgenv().InfJump == true then
                      game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
                  end
              end)
              wait()
          end
      end)
  else
      getgenv().InfJump = false
  end
end)
--infjump.Diskonnekt

SkriptsSection:NewToggle("Infinite jump 2", "use if original doesnt work", function(state)
  if state then
      local InfiniteJumpEnabled = true
    game:GetService("UserInputService").JumpRequest:connect(function()
        if InfiniteJumpEnabled then
            game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
        end
    end)
  else
      InfiniteJumpEnabled = false
  end
end)


SkriptsSection:NewToggle("Auto Jump", "untested", function(state)
  if state then
      while true do wait()
game.Players.LocalPlayer.Character.Humanoid.Jump = true --true~jumping
end
  else
      while true do wait()
game.Players.LocalPlayer.Character.Humanoid.Jump = false --false~jumping
end
  end
end)

SkriptsSection:NewButton("Anti-Fall (for obbys)", "it will tp u to the previous area before u fell",
function()
  -- anti fall
  loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/AntiFall/main/Script"))()

    loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewButton("Aimbot(R6 only)", "simple aimbot skript by me", function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-AIMBOT-SKRIPT-6783"))()
end)

SkriptsSection:NewButton("Aimbot 2 (say /console)", "aimbot", function()

  -- aimbot print 
loadstring(game:HttpGet("https://pastebin.com/raw/i9QLTtbD"))()
end)

-- superhuman
SkriptsSection:NewToggle("Super-Human", "boosts jumppower and speed", function(state)
      if state then
          game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
          game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
      else
          game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
          game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
      end
  end)

SkriptsSection:NewToggle("Sit", "sit/unsit", function(state)
  if state then
      -- sitTrue
game.Players.LocalPlayer.Character.Humanoid.Sit = true
  else
      -- sitFalse
game.Players.LocalPlayer.Character.Humanoid.Sit = false
  end
end)

SkriptsSection:NewButton("what does this do?", "???",
function()
  --???--
loadstring(game:HttpGet("https://pastebin.com/raw/DQ1a5ggY",true))()
end)

SkriptsSection:NewButton("Show chatBox (for games without it)", "good for games like evade w no msg box",
function()
  game:GetService("StarterGui"):SetCoreGuiEnabled('Chat', true)
end)

SkriptsSection:NewButton("Shy Animation (99% fail)", "for 99% fail impossible obby",
function()local ohInstance1 = game.Players.LocalPlayer.Character.Humanoid

game:GetService("ReplicatedStorage").OnRagdoll:FireServer(ohInstance1)

loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewButton("EXEKUTE SKRIPT FROM MESSAGES", "exekute a skript frm msg box",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/chat-executor/main/chat-executor",true))()
end)

SkriptsSection:NewButton("Kredits", "ty to me😍🍭", function()
-- kredits to lulas
game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("LULASLOLLIPOP THE BEST🍭💓🍭💓","All")
end)

SkriptsSection:NewButton("less lag", "FX remover", function()
for _, v in pairs(game:GetService("Workspace"):GetDescendants()) do
  if v:IsA("BasePart") and not v.Parent:FindFirstChild("Humanoid") then
      v.Material = Enum.Material.SmoothPlastic
      if v:IsA("Texture") then
          v:Destroy()
      end
  end
end	

loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewButton("less lag 2 (might dim brightness)", "less rendering", function()
loadstring(game:HttpGet("https://pastebin.com/raw/nHKkMHpN",true))()
end)

SkriptsSection:NewButton("WALKSPEED GUI", "+ -", function()
loadstring(game:HttpGet("https://pastebin.com/raw/2gGvc9ya"))()
end)

SkriptsSection:NewButton("Mood Switxher (yellow/gray)", "yellow grey", function()
loadstring(game:HttpGet('https://pastebin.com/raw/djAd7g2W'))()
end)

SkriptsSection:NewButton("R6 Klimb on walls", "klimb on any walls", function()
loadstring(game:HttpGet('https://pastebin.com/raw/jLVhHEVW'))()

loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewButton("Drag & resize chat", "lets u kontrol the xhat drag and size it", function()
-- drag &resize xhat
loadstring(game:HttpGet("https://pastebin.com/raw/e3KhdyYS"))()

loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewButton("walk on walls (R15 and R6)", "w.o.w", function()
-- walk on walls
loadstring(game:HttpGetAsync("https://pastebin.com/raw/RY9cBbdG"))()
    loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)
SkriptsSection:NewLabel("Mobile Fly guis")
SkriptsSection:NewButton("Fly GUI V2", "mobile fly gui",
function()-- arkeus fly mobile
loadstring(game:HttpGet("https://pastebin.com/raw/Kq7cPe3C"))()
end)
SkriptsSection:NewButton("Fly GUI V3", "fly for mobile",
function()-- v3 fly
loadstring(game:HttpGet("https://raw.githubusercontent.com/rrixh/mobileflygui/main/v3_lulaslollipop",true))()
end)
SkriptsSection:NewButton("Mobile Fly GUI B&W", "modded",
function()--b&w fly gui mobile
    loadstring(game:HttpGet("https://pastecode.dev/raw/hARYYPVGuq/moddedflygui_lulaslollipop",true))()
end)
SkriptsSection:NewButton("Mobile FLY HD ADMIN", "mobile fly HD ADMIN version",
function()-- FLY HD ADMIN
loadstring(game:HttpGet("https://raw.githubusercontent.com/TakeModzz/Ignore-00000/main/Ignore"))()
end)
SkriptsSection:NewButton("Mobile Universal Fly GUI", "speed setter",
function()loadstring(game:HttpGet("https://pastebin.com/raw/YvKv4AuY"))()
end)

--[godmode skripts]--
SkriptsSection:NewLabel("GodMode skripts")
SkriptsSection:NewButton("GodMode (99% fail impossible obby)", "no death 99% fail and some obbys",
function()
  loadstring(game:HttpGet("https://pastebin.com/raw/RWLVhV4N",true))()
end)

SkriptsSection:NewButton("GodMode V2", "no death 99% fail and survive kill brixks",
function()-- fe brixk toggle 
loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/ignore-touchinterests/main/main",true))()
end)
SkriptsSection:NewButton("Universal Godmode", "universal",
function()-- unvrsl godmode 
loadstring(game:HttpGet("https://freenote.biz/raw/Fhpx5r5A8M"))()
end)
--[keybind gens]--
SkriptsSection:NewLabel("⌨️Keybind Gens⌨️")
SkriptsSection:NewButton("KEYBIND GENERATOR", "keyboard letters generator (useful)",
function()
  loadstring(game:HttpGet(('https://pastefy.app/Ujm4HWxh/raw'),true))()
end)
SkriptsSection:NewButton("KEYBIND GENERATOR V2", "keyboard letters generator (useful)",
function()
  -- keybind generator v2
loadstring(game:HttpGet("https://gist.githubusercontent.com/RedZenXYZ/4d80bfd70ee27000660e4bfa7509c667/raw/da903c570249ab3c0c1a74f3467260972c3d87e6/KeyBoard%2520From%2520Ohio%2520Fr%2520Fr"))()
end)
--others--
SkriptsSection:NewLabel("...")
SkriptsSection:NewButton("Mobile Shiftloxk", "shift loxk button",
function()--shiftloxk
loadstring(game:HttpGet("https://pastebin.com/raw/uqAS6EfN"))()
end)

SkriptsSection:NewButton("BETTER Teleport To Player GUI", "V2",
function()loadstring(game:HttpGet("https://gist.githubusercontent.com/DagerFild/b4776075a0d26ef04394133ee6bd2081/raw/0ed51ac94057d2d9a9f00e1b037b9011c76ca54a/tpGUI", true))()
end)

SkriptsSection:NewButton("Lag Switxh V2", "might inkrease FX too,🛜",
function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/Protected - 2023-05-28T225112.055.lua.txt'),true))()
end)

SkriptsSection:NewButton("Translate Messages (fixed)", "type >(language)",
function()loadstring(game:HttpGet("https://pastebin.com/raw/8PRDbzXG"))()
end)
--[mobile keyboard]--
SkriptsSection:NewLabel("Mobile Keyboard")
SkriptsSection:NewButton("Mobile Keyboard", "its a mobile keyboard",
function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
SkriptsSection:NewButton("Better Keyboard", "keyboard gui",
function()-- bettter keyboard 
loadstring(game:HttpGet("https://pastebin.com/raw/X8keCiWA",true))()
end)
--[komputer things]--
SkriptsSection:NewLabel("Komputer")
SkriptsSection:NewButton("KEYBIND STROKES V2", "WASD and spaxe keys",
function()-- KEYSTROKES GUI V2 
loadstring(game:HttpGet(('https://pastefy.app/Te4dwSw2/raw'),true))()
end)

--[[
  {"Esc", "F1", "F2", "F3", "F4", "F5", "F6", "F7", "F8", "F9", "F10", "F11", "F12"},
  {"~", "1", "2", "3", "4", "5", "6", "7", "8", "9", "0", "-", "="},
  {"Tab", "Q", "W", "E", "R", "T", "Y", "U", "I", "O", "P", "[", "]"},
  {"CapsLock", "A", "S", "D", "F", "G", "H", "J", "K", "L", ";", "'", "\\"},
  {"Shift", "Z", "X", "C", "V", "B", "N", "M", ",", ".", "/"},
  {"Ctrl", "Win", "Alt", "Space", "Alt", "Menu", "Ctrl"}
]]
SkriptsSection:NewButton("MOUSE KURSOR", "gives u a mouse kursor touxh",
function()
loadstring(game:HttpGet(('https://pastefy.app/58d8d52G/raw'),true))()
    loadstring(game:HttpGet("https://pastecode.dev/raw/nZaPtHFa5p/lollypop5ever_lulaslollipop",true))()
end)

SkriptsSection:NewLabel("2016-17 roblox")
SkriptsSection:NewButton("fast animations", "player animation will be sped up",
function()-- FAST animations
loadstring(game:HttpGet("https://scriptblox.com/raw/Fast-Animation-FE_744"))()
end)

SkriptsSection:NewButton("old roblox animation", "r6 only",
function()loadstring(game:HttpGet("https://pastebin.com/raw/0ZPiK5ci"))()
end)

SkriptsSection:NewButton("Free R15 emotes", "new&old emotes 2017-23",
function()loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
end)

SkriptsSection:NewButton("Better ROBLOX", "red roblox w stat info",
function()loadstring(game:HttpGet("https://eternityhub.xyz/BetterRoblox/Loader"))()
end)

SkriptsSection:NewButton("2016 roblox UI", "old ui",
function()loadstring(game:HttpGet('https://raw.githubusercontent.com/kosuke14/REBOYHub/main/games/2016_Roblox.lua'))()
end)
SkriptsSection:NewLabel("...")
SkriptsSection:NewButton("RAINBOW MAP", " ",
function()--RAINBOW MAP 
while true do
  for _, part in ipairs(workspace:GetDescendants()) do
      if part:IsA("BasePart") then
          local r = math.random()
          local g = math.random()
          local b = math.random()
          part.BrickColor = BrickColor.new(Color3.new(r, g, b))
      end
  end
  wait(0.5)
end
end)

SkriptsSection:NewButton("SAVE TELEPORT LOKATION", "stand where u want and push add",
function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/Tp%20Place%20GUI'),true))()
end)

SkriptsSection:NewButton("Spy ccTV Kamera", "spy",
function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/CCTV%20Camera'))()
end)

SkriptsSection:NewButton("TOGGLE INVISIBILITY", "prolly not FE",
function()-- toggle invisibility
loadstring(game:HttpGet("https://pastebin.com/raw/HrbT6bNK",true))()
end)

SkriptsSection:NewButton("Freeze POV Kamera", "pov freeze",
function()loadstring(game:HttpGet('https://pastebin.com/raw/T0S0RPTW'))()
end)

SkriptsSection:NewButton("OP SUPER SKREEN STRETXH", "better skreen",
function()local camera = workspace.CurrentCamera
local settings = {
  ["Aspect Ratio"] = true, --// leave it like this if i don't know what You're doing
  ["Ratio Value"] = 0.6 --// leave it like this if i don't know what You're doing
}

local oldNewindex

oldNewindex = hookmetamethod(game, "__newindex", function(object, propertyName, propertyValue)
  if object == camera and propertyName == "CFrame" then
      if settings["Aspect Ratio"] then
          propertyValue = propertyValue * CFrame.new(0, 0, 0, 1, 0, 0, 0, settings["Ratio Value"], 0, 0, 0, 1)
      end
  end
  return oldNewindex(object, propertyName, propertyValue)
end)
end)

SkriptsSection:NewButton("Never Ending Bloxk Spawner", "good for lagging servers",
function()local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local part = Instance.new("Part")
part.BrickColor = BrickColor.new("Bright blue")
part.Size = Vector3.new(5, 5, 5)

while true do
  local position = character.PrimaryPart.Position
  local randomOffset = Vector3.new(math.random(-10, 10), math.random(-10, 10), math.random(-10, 10))
  part:Clone().Parent = workspace
  part.Position = position + randomOffset
  wait(0.4) -- adjust the delay between spawns if u want
end
end)

SkriptsSection:NewButton("KLEAR MESSAGES TROLL", "prints a huge text msg",
function()
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(" ⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻", "All")
end)

SkriptsSection:NewButton("Parkour Run", "no speed limit,FOV & speed",
function()-- fe parkour 
loadstring(game:HttpGet("https://pastebin.com/raw/R5YR13pG"))()
end)

SkriptsSection:NewButton("R15 to R6", "only work if u are r15",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua", true))()
end)

SkriptsSection:NewButton("Noklip", "go thru walls",
function()loadstring(game:HttpGet("https://pastebin.com/raw/3wf2wpBW"))()
end)

SkriptsSection:NewButton("Spektate", "spektate players",
function()loadstring(game:HttpGet("https://pastebin.com/raw/daM0ut53"))()
end)

SkriptsSection:NewButton("GreenSkreengui", "not fe but perfekt for videos", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Green%20Screen'))()
end)

local SkriptsSection = Skripts:NewSection("ESP")

SkriptsSection:NewButton("Minekraft ESP", "shows all usernames and esp",
function()-- ESP PIXELGAME
loadstring(game:HttpGet("https://paste.gg/p/anonymous/7259b0557ebf44ccabf2f7b58dc79899/files/0475cb5d744642a2b572e3a8af205588/raw"))()
end)

SkriptsSection:NewButton("Show Usernames ESP", "shows all usernames and esp",
function()loadstring(game:HttpGet("https://pastebin.com/raw/hpMC6ULU"))()
end)

SkriptsSection:NewButton("Shadow ESP", "see players thru walls but shadows",
function()loadstring(game:HttpGet("https://pastebin.com/raw/QQqiFGTE"))()
end)

SkriptsSection:NewButton("Purple ESP", "see players highlighted purple",
function()loadstring(game:HttpGet("https://pastebin.com/raw/7K1Jhmck"))()
end)

local SkriptsSection = Skripts:NewSection("Exekutors")

-- exekutors below label
SkriptsSection:NewButton("Arkeus X Exekutor", "android exekutor works for ios",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/Arceus%20X%20V3"))()
end)
SkriptsSection:NewButton("KRNL Exekutor", "an exekutor",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/Chillz-s-scripts/main/KRNL%20UI%20Remake.lua"))()
end)
SkriptsSection:NewButton("Neptune Exekutor", "an exekutor",
function()-- neptune exe
loadstring(game:HttpGet('https://pastebin.com/raw/y3jhxS5r'))()
end)
SkriptsSection:NewButton("Rc7 exekutor(old)", "request by emil", function()
--[[
Rc7 exe gui old
]]
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Project-RC7-6752"))() 
end)
SkriptsSection:NewButton("Rc7 exekutor(new)", "request by emil", function()
--[[
Rc7 exe gui new
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/CoreGui/Scripts/main/RC7"))() 
end)
SkriptsSection:NewButton("Synapse X (old gui)", "synapse x",
function()loadstring(game:HttpGet("https://pastebin.com/raw/1fAnGAA0"))()
-- Synapse x skript old gui
end)
SkriptsSection:NewButton("Synapse X", "shadow x",
function()loadstring(game:HttpGet("https://pastebin.com/raw/2qjBZB1Y"))()
-- shadow x exe gui
end)
SkriptsSection:NewButton("Nokom exe", "shadow x gui",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/NoCom-Executor/main/NoCom"))()
-- nokom exe gui
end)
SkriptsSection:NewButton("Exekutor gui", "exe gui",
function()
  loadstring(game:HttpGet("https://pastebin.com/raw/yGxeT8zC", true))()
  -- exekutor gui
end)




--r15 animationz
local SkriptsSection = Skripts:NewSection("R15 Animation")

SkriptsSection:NewButton("Zombie Animation", "R15 animation", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
  end
end
end)
SkriptsSection:NewButton("Kartoony Animation", "R15 animation", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
  end
end
end)

SkriptsSection:NewButton("Astronaut", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
   end
end
end)

SkriptsSection:NewButton("Bubbly", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=910004836"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=910009958"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=910034870"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=910025107"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=910016857"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=910001910"
Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=910030921"
Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=910028158"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
   end
end
end)

SkriptsSection:NewButton("Elder", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=845400520"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=845403856"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=845386501"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=845398858"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=845392038"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=845396048"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end) 

SkriptsSection:NewButton("Knight", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616010382"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616003713"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end 
end)

SkriptsSection:NewButton("Levitation", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Mage", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)
SkriptsSection:NewButton("Ninja", "lokal skripts", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Pirate", "lokal skripts", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Robot", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Stylish", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Superhero", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end 
end 
end)

SkriptsSection:NewButton("Toy", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Vampire", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083445855"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083450166"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083473930"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083462077"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083455352"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083439238"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083443587"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Werewolf", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1083195517"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1083214717"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1083178339"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1083216690"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1083218792"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1083182000"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1083189019"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Patrol", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1149612882"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1150842221"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1151231493"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1150967949"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1148811837"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1148863382"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Konfident", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=1069977950"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=1069987858"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=1070017263"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=1070001516"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=1069984524"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=1069946257"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=1069973677"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Ghost", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Sneaky", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616006778"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616008087"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616013216"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616008936"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616005863"
Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=616012453"
Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=616011509"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Prinxess", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=941003647"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=941013098"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=941028902"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=941015281"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=941008832"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=940996062"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=941000007"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("No Animation", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.swimidle.SwimIdle.AnimationId = "http://www.roblox.com/asset/?id=0"
Animate.swim.Swim.AnimationId = "http://www.roblox.com/asset/?id=0"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
end)

SkriptsSection:NewButton("Athro", "lokal skript", function()
while true do
  wait(1)
  for i, player in ipairs(game.Players:GetChildren()) do
  local Animate = game.Players.LocalPlayer.Character.Animate
local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=2510196951"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=2510197257"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=2510202577"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=2510198475"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=2510197830"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=2510192778"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=2510195892"
  game.Players.LocalPlayer.Character.Humanoid.Jump = false
end
end
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
AdminSection:NewButton("Reviz Admin", "default prefix ; say ;cmds", function()
loadstring(game:HttpGet("https://pastebin.com/raw/RqaZUrBZ"))()
end)
AdminSection:NewButton("Nameless Admin", "type ;cmds", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)
AdminSection:NewButton("Universal Admin Panel", "admin panel", function()
-- unvrsl admin --
loadstring(game:HttpGet(('https://pastefy.app/Oic24KzG/raw'),true))()
end)
AdminSection:NewButton("IV Admin v3", "admin kommands", function()
--[[
Iv admin v3
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/BloodyBurns/Hex/main/Iv%20Admin%20v3.lua"))()
end)
AdminSection:NewButton("IV Admin", "admin kommands", function()
--[[
Iv admin
]]
  loadstring(game:HttpGet("https://pastecode.dev/raw/yX8bQ6ZgUe/ivadmin",true))()
end)
AdminSection:NewButton("Hextus Admin", "admin logs", function()
--[[
hextux admin 1.0.2
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/BonBonTheDev/Hextus/main/Hextus.lua",true))()
end)
AdminSection:NewButton("Vortex Admin", "admin", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Sidhsksjsjsh/Fe-Vortex-admin-V2/main/VortexCompany/C4/Discord.lua"))() 
    -- fe vortex admin
end)
AdminSection:NewButton("Brixk Admin", "rewrite", function()
loadstring(game:HttpGet("https://pastecode.dev/raw/uaxYupfcaQ/rewriteBrixkAdmin_lulaslollipop",true))()
end)

AdminSection:NewButton("Property Admin", "property", function()
--[[
property admin
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/Copinface/MainSource/main/PropertyAdmin"))()
end)
AdminSection:NewButton("Lion Admin", "property", function()
--[[
lion admin
]]
  loadstring(game:HttpGet("https://raw.githubusercontent.com/WCodesEz/Lion-Admin/main/v1.lua"))()
end)
AdminSection:NewButton("Unknown Admin", "hmm", function()
--[[
unknown admin
]]
  loadstring(game:HttpGet("https://gist.github.com/someunknowndude/38cecea5be9d75cb743eac8b1eaf6758/raw"))()
  -- someunknowndude Admin 
end)
AdminSection:NewButton("Legs Admin v2", "leg day", function()
--[[
legs admin v2
]]
  loadstring(game:HttpGet('https://raw.githubusercontent.com/leg1337/legadmv2/main/legadminv2.lua'))()
  -- Legs admin v2 
end)
AdminSection:NewButton("ShatterVast Admin", "shattervast old", function()
--[[
shattervast admin
]]
  loadstring(game:HttpGet("https://pastebin.com/raw/m66HEHFu"))()
  -- ShatterVast admin
end)

-- OTHER ADMINS

local AdminSection = Admin:NewSection("Troll Admin")

AdminSection:NewButton("Annoying Admin", "type .cmds and then /console to see kmd list", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/TheMightySource/FE-Annoying-Admin/main/Main.lua'),true))()
end)
AdminSection:NewButton("Simple Admin", "type .cmds, say (.set prefix ;) to set ; instead of .", function()loadstring(game:HttpGet('https://pastebin.com/raw/3hDQcTaD'))()
end)



-- Fun SKRIPTS
local Fun = Window:NewTab("Fun")
local FunSection = Fun:NewSection("Animations")

FunSection:NewButton("Lolly Animations", "work r15 and r6", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/yeerma/1/main/the_greatest_script_ever_made'))()
end)
FunSection:NewButton("Energyze Animations", "work r15 and r6", function()loadstring(game:HttpGet(('https://pastebin.com/raw/1p6xnBNf'),true))()
end)
FunSection:NewButton("Be A Helikopter", "human xhoppa", function()-- laydown spin/helikopter
loadstring(game:HttpGet("https://pastebin.com/raw/XP8yfVbk"))()
end)
FunSection:NewButton("Krawl", "simple krawl gui", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/0Ben1/fe/main/obf_vZDX8j5ggfAf58QhdJ59BVEmF6nmZgq4Mcjt2l8wn16CiStIW2P6EkNc605qv9K4.lua.txt'))()
end)
FunSection:NewButton("R6 pose gui", "pose📸",
function()loadstring(game:HttpGet('https://pastebin.com/raw/sZMn81tZ'))()
end)


local FunSection = Fun:NewSection("Message Fun")

FunSection:NewButton("Fake Message Troll", "type for others", function()
loadstring(game:HttpGet('https://pastebin.com/raw/MBpnp3yS'))()
end)
FunSection:NewButton("Diskord Emojis [example: :angry:]", "type the emoji name in between the kolons", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/rrixh/diskord_emojis/main/emojis_lulaslollipop",true))()
end)

FunSection:NewButton("Spell Out Any Kurseword (use L tool given)", "use L tool to open/klose gui", function()
-- spell out kurse word
loadstring(game:HttpGet("https://pastebin.com/raw/xinPiBSU"))()
  loadstring(game:HttpGet("https://pastebin.com/raw/QzxqjgSf"))()
end)
FunSection:NewButton("Kompliment Random Player", "push to kompliment a random player", function()
loadstring(game:HttpGet("https://pastebin.com/raw/0n4YDguK"))()
end)
FunSection:NewButton("Kompliment V2", "makes u say a kompliment", function()
loadstring(game:HttpGet("https://pastebin.com/raw/0HidbJsd"))()
end)
FunSection:NewButton("Auto Exkuse", "auto msg wen u die", function()
getgenv().dmsgs = {
deathmessages = {"i was lagging", "that wasnt fair", "bruh", "dude", "i was doing something", "whyyyyy", "that wasnt fair", "wow"}
}
--[[
Auto-Exkuse
]]--
loadstring(game:HttpGet("https://raw.githubusercontent.com/goldmoments/auto-excuse/main/Script"))("Auto-Exkuse Script | lulaslollipoo#0140") 
end)
FunSection:NewButton("Kopy Server Messages", "repeats all players messages", function()local ReplicatedStorage = game:FindService("ReplicatedStorage")
local ChatEvents = ReplicatedStorage:WaitForChild("DefaultChatSystemChatEvents")
local OnMessageEvent = ChatEvents:WaitForChild("OnMessageDoneFiltering")
local SayMessageRequest = ChatEvents:WaitForChild("SayMessageRequest")

if not SayMessageRequest:IsA("RemoteEvent") or not OnMessageEvent:IsA("RemoteEvent") then return end

local ChatLegth = require(game:FindService("Chat"):WaitForChild("ClientChatModules"):WaitForChild("ChatSettings")).MaximumMessageLength
local lp = game:FindService("Players").LocalPlayer.Name

OnMessageEvent.OnClientEvent:Connect(function(data)
  if not data then return end
  local player = tostring(data.FromSpeaker)
  if player == lp then return end
  local message = tostring(data.Message)
  if (message):len() <= (ChatLegth-7) then
      SayMessageRequest:FireServer(('\%s'):format(message,""),tostring(data.OriginalChannel))
  end
end)
end)

FunSection:NewButton("Nerd Quote", " repeats all msgs with a nerd quote", function()local ReplicatedStorage = game:FindService("ReplicatedStorage")
local ChatEvents = ReplicatedStorage:WaitForChild("DefaultChatSystemChatEvents")
local OnMessageEvent = ChatEvents:WaitForChild("OnMessageDoneFiltering")
local SayMessageRequest = ChatEvents:WaitForChild("SayMessageRequest")

if not SayMessageRequest:IsA("RemoteEvent") or not OnMessageEvent:IsA("RemoteEvent") then return end

local ChatLegth = require(game:FindService("Chat"):WaitForChild("ClientChatModules"):WaitForChild("ChatSettings")).MaximumMessageLength
local lp = game:FindService("Players").LocalPlayer.Name

OnMessageEvent.OnClientEvent:Connect(function(data)
  if not data then return end
  local player = tostring(data.FromSpeaker)
  if player == lp then return end
  local message = tostring(data.Message)
  if (message):len() <= (ChatLegth-7) then
      SayMessageRequest:FireServer(('\"%s\"%s'):format(message,"🤓"),tostring(data.OriginalChannel))
  end
end)
end)

FunSection:NewButton("Rainbow Messages", "enables xhat bubble and see msg frm far away", function()
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

          MaxBubbles = 20,

          -- Styling for the bubbles. These settings will change various visual aspects.

          BackgroundColor3 = Color3.fromRGB(0, 0, 0),

          TextSize = 16,

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

          MinimizeDistance = 250,

          -- The max distance (from the camera) that bubbles are shown at

          MaxDistance = 2222,

      })

  end)

end
end)

FunSection:NewButton("SpamHub", "sing songs etx.", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/ColdStep2/Chatdestroyer-Hub-V1/main/Chatdestroyer%20Hub%20V1'),true))()
end)
FunSection:NewButton("Lyrik Bot (say: >lyrics SongName by ArtistName)", "sing songs requested by other users", function()
  local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
  Library.DefaultColor = Color3.fromRGB(50,205,50)

  Library:Notification({
    Text = ">lyrics SongName by AristName (doesnt work for urself)",
    Duration = 7
  })

loadstring(game:HttpGet("https://raw.githubusercontent.com/CF-Trail/lyricsBot/main/singer.lua"))()
end)
FunSection:NewButton("BetterBypasser", "hmmmm", function()
loadstring(game:HttpGet("https://gist.githubusercontent.com/lexsplorsex/b4b3b1243329327faec92f6953d4ed02/raw/a144202fc87db6493a109bf91a7cd14445e012ec/gistfile1.txt"))()
end)


local FunSection = Fun:NewSection("Humanoid")

FunSection:NewButton("Destroy Body", "yea", function()
loadstring(game:HttpGet("https://pastebin.com/raw/naRUdxrc", true))()
end)

FunSection:NewButton("fake lag", "lag for fun",
function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Fe%20Fake%20Lag%20Obfuscator'))()
end)

-- tools tab
local Tools = Window:NewTab("Tools")
local ToolsSection = Tools:NewSection("Tools")

ToolsSection:NewButton("BTools", "building tools", function()
b = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
b.BinType = 4 --del
c = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
c.BinType = 3 --kopy
end)--kopy&del
ToolsSection:NewButton("Delete Tool", "the Delete building tool", function()
b = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
b.BinType = 4 
end)--end.deletetool
ToolsSection:NewButton("Kopy Tool", "the Kopy building tool", function()
b = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
b.BinType = 3
end)--end.kopytool
--end btools.Tools tab
ToolsSection:NewButton("Tp To Player GUI (small)", "small like zuki", function()
loadstring(game:HttpGet(("https://pastebin.com/raw/YNVbeqPy")))()
end)
ToolsSection:NewButton("Free Gear Tools 🧨", "💣⚙️👊🏽⛓️fun", function()
loadstring(game:HttpGet(('https://pastefy.app/VYIAk3o1/raw'),true))()
end)

ToolsSection:NewButton("F3X", "good for darkness and horror games",
function()
  local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/Revenant", true))()
Library.DefaultColor = Color3.fromRGB(50,205,50)

Library:Notification({
  Text = "f3x tools sinxe u wna be bob the builder",
  Duration = 5
})
  --tools
  loadstring(game:GetObjects("rbxassetid://6695644299")[1].Source)()
  --F3X skript
end)

ToolsSection:NewButton("KAKE/KAIK Tool", "gives u a kake tool to throw", function()
  -- KAIK 🎂 TOOL
loadstring(game:HttpGet("https://textbin.net/raw/tccg5bly5b"))()
end)

ToolsSection:NewButton("Teleknesis", "works in games like brookhaven,dahood etx.", function()
loadstring(game:HttpGet("https://pastebin.com/raw/vVze4jgA",true))()
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

ToolsSection:NewButton("Invisible Tool", "hides and unhides your body in the air", function()
loadstring(game:HttpGet("https://pastebin.com/raw/LraZZsaZ",true))()
end)

ToolsSection:NewButton("Disabled Tools", "key:AdminTools", function()
loadstring(game:HttpGet('https://pastebin.com/raw/0BsHnxbk'))()
end)

-- KEybind tools
ToolsSection:NewButton("{Q} Tool", "give u Q key from 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/5ZgW4X4q"))()
end)

ToolsSection:NewButton("{Z} Tool", "give u Z key from 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/HVTtz0JU"))()
end)

ToolsSection:NewButton("{X} Tool", "give u X key from 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/VkFTvruh"))()
end)

ToolsSection:NewButton("{C} Tool", "give u C Key from 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/wgxcSj5N"))()
end)
--Insert.keynum.toggle
ToolsSection:NewButton("Toggle Tool", "gives u the 'Toggle' button as a tool {Insert}",
function()loadstring(game:HttpGet("https://pastebin.com/raw/CjnNRWnK"))()
end)

ToolsSection:NewButton("{RightKontrol} Tool", "gives u the right ktrl key frm 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/sD1NK6a7"))()
end)

ToolsSection:NewButton("{LeftKontrol} Tool", "gives u the left ktrl button frm 💻 as a tool",
function()loadstring(game:HttpGet("https://pastebin.com/raw/NdEpUa4k"))()
end)



-- hubs and gui
local Hub = Window:NewTab("Hubs & GUIs")
local HubSection = Hub:NewSection("everything u need😋🍭")

HubSection:NewButton("99% fail impossible obby teleport gui", "small tp gui by me", function()
loadstring(game:HttpGet("https://pastebin.com/raw/HQY7LiGn"))()
end)

HubSection:NewButton("Universal OP Shiftloxk gui", "shiftloxk ", function()
-- shiftloxk gui op
  loadstring(game:HttpGet("https://scriptblox.com/raw/Baseplate-Universal-Script-Permanent-Shift-Lock-6924"))()
end)

HubSection:NewButton("Keybind Tools GUI (unfinished)", "simple keybind gui", function()
loadstring(game:HttpGet("https://pastebin.com/raw/1xrhfTD5"))()
end)

HubSection:NewButton("ASTRAL HUB V3", "a hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/AstralHub/main/Main.lua", true))()
end)

HubSection:NewButton("Harsh Texh v7.4", "lots of skripts", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Beta/main/HarshTech7.4.lua'),true))()
end)

HubSection:NewButton("Skript Loader", "huge GUI", function()
loadstring(game:HttpGet("https://pastebin.com/raw/zzYSdwhk", true))()
end)

HubSection:NewButton("Games Hub V5 (fixed)", "fixed", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/TakeModzz/Games-Hub-V5-Selector-Fixed/main/Games"))()
end)

HubSection:NewButton("Anime Hub 😍", "v6.1", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/TakeModzz/Games-Hub-Script/main/Games%20Hub%20(Always%20updated)"))()
end)

HubSection:NewButton("LegonX Hub", "kool and Many skripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/Loadstring/main/LegonX"))()
end)

HubSection:NewButton("KOLLISION GUI", "toggls player kollision",
function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/Collision.txt'),true))()
end)

HubSection:NewButton("BIDO SKINS V1.5", "HELLA SKRIPTS", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BidoSkinsYT/BidoSkinsYT/main/Bido%20SkinsV1.5"))()
end)

HubSection:NewButton("GHOST Hub BEST", "HELLA SKRIPTS", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)

HubSection:NewButton("REDGHOST Hub", "gameshub", function()
loadstring(game:HttpGet('https://pastebin.com/raw/WFKSRG6m'))();
end)

HubSection:NewButton("Darkrai X Animation Hub v0.3", "FREE ANIMS R15", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
end)

HubSection:NewButton("Simple v3", "simple v3 hub", function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Simple-V3-8819", true))()
end)

HubSection:NewButton("Abuse GUI", "abuse", function()
loadstring(game:HttpGet("https://pastebin.com/raw/2XnDKHcH"))()
end)

HubSection:NewButton("Davi hub", "games hub", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Davicoderliner/davigui/main/Daviguiv2loader.lua"),true))()
end)

HubSection:NewButton("Mini hub", "games hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/MiniNoobie/MINI-HUB-V2/main/FINALLY%20UPDATED%20MINI%20HUB",true))()
end)

HubSection:NewButton("SPIDERMAN ABILITY GUI", "klimb walls (C to toggle)", function()
--SPIDER MAN GUI
loadstring(game:HttpGet(('https://pastebin.com/raw/2X0hKUgq'),true))()
end)

HubSection:NewButton("Universal Spy GUI", "player list gui", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/MichaelScripter/MiniScript/main/Spy gui.lua"))()
end)
HubSection:NewLabel("Fling guis")
HubSection:NewButton("Fling GUI", "fling a player by walking into them", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
end)

HubSection:NewButton("fling Animator", "👊🏽👊🏽👊🏽👊🏽👊🏽", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_K2n31uc6t2wY5A8786eR4K15sgbUF0vdQ80a0LzgvLRkSNYd89H1AS3124gMR6SM.lua.txt'),true))()
end)

HubSection:NewButton("Fling - press a player", "fling a player by pressing them", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_5wpM7bBcOPspmX7lQ3m75SrYNWqxZ858ai3tJdEAId6jSI05IOUB224FQ0VSAswH.lua.txt'),true))()
end)
HubSection:NewButton("Universal Fling gui", "fling a player by pressing them", function()
loadstring(game:HttpGet("https://paste.ee/r/NTtmf", true))()
end)
HubSection:NewLabel("...")
HubSection:NewButton("Ohio Hub", "small hub", function()
--Ohio GUI
loadstring(game:HttpGet("https://pastebin.com/raw/hkvHeHed",true))()
end)

HubSection:NewButton("Darkrai X", "hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/arsenal-hub/main/Arsenal%20GamingScripter", true))()
end)

HubSection:NewButton("B Genesis V1.2", "hub", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/raw-scriptpastebin/raw/main/B_Genesis'))()
end)

HubSection:NewButton("Moon ui", "moon gui", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)

HubSection:NewButton("RTX GUI", "map kolor/theme editor",
function()loadstring(game:HttpGet(('https://pastefy.app/xXkUxA0P/raw'),true))()
end)

HubSection:NewButton("RTX GUI 2", "map kolor/theme editor", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/Chillz-s-scripts/main/enhancer.txt"))()
end)

HubSection:NewButton("FE RemX OP trolling gui", "trolling gui", function()
loadstring(game:HttpGet("https://pastebin.com/raw/6TGpAUjr"))()
end)

HubSection:NewButton("Giga Hub", "hella skripts", function()-- Giga xhad hub
loadstring(game:HttpGet('https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Version%20V3.5'))()
end)

HubSection:NewButton("Ez Hub", "yea", function()-- ez hub
loadstring(game:HttpGet("https://scriptblox.com/raw/Ez-Hub_168"))()
end)

HubSection:NewButton("Heart Ui", "heart hub", function()loadstring(game:GetObjects("rbxassetid://1313915586")[1].Source)()
end)

HubSection:NewButton("KoolGui", "4+ skripts", function()
loadstring(game:HttpGet("https://pastebin.com/raw/n3FDLDh3"))()
end)

HubSection:NewButton("RemX Gui", "old But Op", function()
 loadstring(game:HttpGet(('https://raw.githubusercontent.com/Henry887/RemX-Script-Hub/main/main.lua'),true))()
end)

HubSection:NewButton("Legon Hub", "Op hub with alot of skripts", function()
  loadstring(game:HttpGet('https://pastebin.com/raw/B1cUSJsv'))()
end)

HubSection:NewButton("Bloodfest GUI", "game Gui lol", function()
loadstring(game:HttpGet("https://pastebin.com/raw/MyuKiH2q", true))()
end)

HubSection:NewButton("ZenHub", "hella skripts", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/KaiZen/main/GameHub", true))()
end)

HubSection:NewButton("HubSkriptWithNoHat", "dont ask about the name", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/tyreltrijo/firex/main/firex'))()
end)

HubSection:NewButton("ProHubV2", "Similar To BritishHub", function()
--PROHUB V.2--
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.2/main/Is%20here"), true))()
end)

HubSection:NewButton("BritishHubV6", " like Prohub", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/BHob6"),true))()
end)

HubSection:NewButton("Vhub", "A big Gui full of skripts for trolling etx.", function()
  -- is a loadstring skript bekause skript is to large >https://roblxopayscript.godaddysites.com<

loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt'),true))()
end)

HubSection:NewButton("MegaHub(30+ Feature)", " ", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/WholeF00ds/Mega/main/Obfuscated%20Loader'),true))()
end)

HubSection:NewButton("Vhub 1.2.4(New Version)", "vhub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SourceScript5315/sauce/main/VH-Launcher.lua"))()
end)

HubSection:NewButton("K00lK1D Gui V2", "So Skary", function()
loadstring(game:GetObjects("rbxassetid://9827584846")[1].Source)()
end)

HubSection:NewButton("Kindasu Hub", "New Gui", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.1-beta/main/Fixed%20bugs%20v.1%20beta"), true))()
end)

HubSection:NewButton("Pro Hub", "New Gui", function()loadstring(game:HttpGet("https://pastebin.com/raw/hecGHj99"))()
end)

HubSection:NewButton("KZS Hub", "idk ._.", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/KZSHUB/KZS-HUB/main/KZSHUBV1.5", true))()
end)

HubSection:NewButton("Frixon Hub", "Eee idk", function()
  loadstring(game:HttpGet('https://gist.githubusercontent.com/RedoGaming/459eb467f3df927b07ca398a68f3b053/raw/6d1f7a2c8fefd072dc53ebbbec38c6f93c7de1ad/Frixon%2520Hub!%2520New%2520OP%2520Exploit%2520Hub%2520for%2520Roblox!'))()
end)

HubSection:NewButton("RageFlake Hub", "Lol", function()
  loadstring(game:HttpGet('https://gist.githubusercontent.com/RedoGaming/2e5943498c487ea97df0d436dd35c234/raw/f0445b1afcd9193bfb94bc75dda7318310a22ad2/Rageflake!%2520New%2520OP%2520Roblox%2520Exploit%2520Hub!'))()
end)

HubSection:NewButton("Zen Hub", "Eeeeee idk", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/KaiZen/main/GameHub", true))()
end)

HubSection:NewButton("Ultimate Trolling Gui V3", "utg old", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))() 
end)

HubSection:NewButton("Psy Hub", "Op and has an exekutor i think", function()
loadstring(game:GetObjects("rbxassetid://3014051754")[1].Source)()
end)

HubSection:NewButton("Gamehub V4", "request by emil", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Game-Hub/main/loader"))()
end)

HubSection:NewButton("Gigachad Hub V7", "request by emil", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/LolPrivate/Side/main/Gigachad%20Hub%20V7.lua", true))()
end)

HubSection:NewButton("FathomHub", "request by emil", function()
--[[
fathomhub
]]
loadstring(game:HttpGet("https://pastebin.com/raw/Y4AGJALY"))();
end)

HubSection:NewButton("OrangeX Hub V5", "request by emil", function()
--[[
orange x hubv5
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/ImJosh66/Ab2rW/main/ORANGEX%20V5%20RELEASED%20ORANGEX%20ON%20TOP%20.txt"))()
end)

HubSection:NewButton("Multi-Skripter Hub V3", "request by emil", function()
--[[
multi skripter hubv3
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Multi-Scripter-X/main/loader"))()
end)

HubSection:NewButton("British Hub V15", "request by emil", function()
  --britishhub v15
loadstring(game:HttpGet("https://raw.githubusercontent.com/RedCoat8102/Britishhub/main/Protected_7002515694901812.lua.txt", true))()
end)
HubSection:NewButton("British Hub V16 (new)", "request by emil", function()
  --britishhub v16 new
loadstring(game:HttpGet("https://raw.githubusercontent.com/1tsFire/Br1tishHub/main/Protected_6883620778116350.lua.txt", true))()
end)
HubSection:NewButton("Thunder Hub", "request by emil", function()
  --thunderhub
loadstring(game:HttpGet('https://pastebin.com/raw/DFjY4nMy'))()
end)
HubSection:NewButton("Davi hub v2.2", "request by emil", function()
--[[
davi hub2.2
]]
loadstring(game:HttpGet('https://raw.githubusercontent.com/Davicoderliner/davigui/main/davi.lua'))()
end)
HubSection:NewButton("Ultimate troll hub 2.2 (new version)", "request by emil", function()
--[[
ultimate troll hub 2.2
]]
loadstring(game:HttpGet('https://raw.githubusercontent.com/AkilExploitz/AkilBlox14-s-Script-Hub-v1.1/main/Utg%202.2%20startup'))()
end)
HubSection:NewButton("AuratusX", "request by emil", function()
--[[
AuratusX
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/RealMrQuacks/AuratusX/master/Load"))() 
end)
HubSection:NewButton("Bido skins v1.8 (new)", "request by emil", function()
--[[
Bido skins 1.8 new version
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/BidoSkinsYT/BidoSkinsYT/main/Bido%20Skins%20V1.8"))()
end)
HubSection:NewButton("Haxker_6666666 Hub V2.8", "o:", function()
--[[
Haxker_666 hub fixed
]]
loadstring(game:HttpGet('https://raw.githubusercontent.com/FreeRobloxScripts1/Haxker_6666666-Hub/main/Script-Hub/Version-2.8'))()
end)
HubSection:NewButton("Ghub ui v7", "good hub", function()
--[[
ghub ui v7
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/Ghubv7/main/ghub%20v7.lua"))()
end)
HubSection:NewButton("Holf Hub", "idek what holf is", function()
--[[
holf hub
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/Podroka626/Scripts/main/Universal"))()
end)
HubSection:NewButton("Rayfield hub", "idek what holf is", function()
--[[
rayfield hub
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/Essinity/Rayfield-Hub/main/Script", true))()
end)
HubSection:NewButton("ExtremeX hub v2", "request by emil", function()
--[[
extremeX hub v2
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/Evv2/main/Protected_3951169998210840.lua.txt"))()
end)
HubSection:NewButton("Moon ui v13", "request by emil", function()
--[[
moon ui v13
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/IlikeyocutgHAH/MoonUI-v13-102-SCRIPTS/main/MoonUI%20v13!"))()
end)
HubSection:NewButton("Juanko Universal Hub", "juanko universal", function()
--[[
juanko unvrsl hub
]]
loadstring(game:HttpGet("https://pastebin.com/raw/d5BS5qiX"))() 
end)
HubSection:NewButton("Alysee hub", "request by emil", function()
--[[
alysee hub
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/NathTheDev/AlysseAndroid/main/loader.lua"))()
end)
HubSection:NewButton("Astronlynx hub", "request by emil", function()
--[[
Astronlynx hub
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/1tsFire/Astrolynx/main/AstrolynxScripts.lua", true))()
end)
HubSection:NewButton("Astronlynix hub 0.4 (new version)", "request by emil", function()
--[[
Astronlynix hub
]]
loadstring(game:HttpGet("https://freenote.biz/raw/vBfN3NeVYN", true))()
end)
HubSection:NewButton("Universal c9 Hub", "request by emil", function()
--[[
C9 hub unvrsl
]]
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-C9-HUB-UNIVERSAL-Fully-released-8516"))()
end)
HubSection:NewButton("Ghub ui V8 (new version)", "request by emil", function()
--[[
Ghub ui v8 new version
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBUIV8/main/GhubUIv8.txt"))()
end)
HubSection:NewButton("Ghub ui V8 (old version)", "request by emil", function()
--[[
Ghub ui v8 old version
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBUIV8/main/GhubUIv8.txt"))()
end)
HubSection:NewButton("Ghub ui V9 (new)", "request by emil", function()
--[[
Ghub ui v9 new
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/Ghub-v9/main/Ghubv9UI.txt"))()
end)
HubSection:NewButton("TMR X(new version) (fixed)", "fixed", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/TakeModzz/TMR-X/main/Script"))()
  -- Tmr x hub new version and fixed
end)
HubSection:NewButton("K00lkidd gui revival (old)", "k00lkid gay", function()
--[[
K00lkidd gui revival old
]]
loadstring(game:HttpGet(("https://raw.githubusercontent.com/theawesomari0/c00lgui/main/c00lgui"), true))()
end)
HubSection:NewButton("K00lkidd gui revival (new)", "k00lkid new gayahh gui", function()
--[[
  K00lkidd gui revival new
]]
loadstring(game:HttpGet(("https://raw.githubusercontent.com/theawesomari0/c00lgui/66033e8ff67eccc421fb04b3924e42d4adf3d7a2/c00lgui%20v2.2"), true))()
end)
HubSection:NewButton("K00lkidd gui revival 2.3(new version)", "k00lkidd", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/theawesomari0/c00lgui/main/c00lgui%20v2.3", true))()
    -- k00lkidd gui revival 2.3 new version
end)
HubSection:NewButton("Hydro hub", "blah", function()
--[[
  Hydro hub
]]
  loadstring(game:HttpGet("https://raw.githubusercontent.com/FRX397/Hydrohub/main/Hydro_hub", true))()
end)
HubSection:NewButton("The hub v3", "theeeee hub", function()
--[[
  The hub v3
]]
  loadstring(game:HttpGet("https://raw.githubusercontent.com/hassantheking123321/TheHub/main/The%20hub%20v3%20test",true))()
end)
HubSection:NewButton("Universal Shakars hub", "what the hell", function()
--[[
  Universal shakars hub
]]
  loadstring(game:HttpGet("https://raw.githubusercontent.com/shakar60/USH.P/main/rotected",true))()
end)
HubSection:NewButton("VersionHub V2.3.1", "a hub", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/ScripterGamerBobux/VersionHub/main/V2.3.1.lua.txt",true))()
  -- Version hub
end)
HubSection:NewButton("Versus hub (LoaderV2)", "LoaderV2", function()
  loadstring(game:HttpGet("https://gitlab.com/Ner0ox/versus/-/raw/main/LoaderV2/Loader.lua"))()
  -- Versus  hub
end)
HubSection:NewButton("Dex skripthub", "binarydex", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/BinaryDex/DexHub/main/Init"))()
  --Dex hub
end)
HubSection:NewButton("Spanish hub v4", "no ingles", function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-SPANISH-HUB-V4-THE-GOAT-HUB-8429"))()
  --Spanish v4 hub
end)
HubSection:NewButton("GLoader hub", "g loader", function()
  loadstring(game:HttpGet("https://github.com/GroceyLot/My-roblox-stuff/raw/Things/GLoader.lua"))()
  --Gloader hub
end)
HubSection:NewButton("Spaxe hub", "orbituniverse", function()
  loadstring(game:HttpGet("https://orbituniverse.com/spacehub"))()
  --Spaxe hub
end)

HubSection:NewButton("Lego hub v3", "lego", function()
  loadstring(game:HttpGet("https://comensal.is-not-a.dev/legohub"))()
  -- Lego hub v3
end)

HubSection:NewButton("Balkan hub x v3", "by balkan", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Balkanx/Balkan-x/main/Balkan%20x", true))()
  -- Balkan hub x v3
end)

HubSection:NewButton("BUTIF Universal hub", "by BUTIF", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NEWBUTIF/Universal-Script-Hub/main/Butif%20Hub%202"))()
    -- Butif universal hub
end)
HubSection:NewButton("Plenem hub", "pyea", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Plenum-Hub/main/loader"))() 
    -- plenum hub
end)
HubSection:NewButton("BritishHub v1.7 (fixed)", "fixed 1.7", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RedCoat33/Britishhub/main/Protected_7358793088278524.lua.txt", true))()
    -- british hub v1.7 (fixed) new version
end)
HubSection:NewButton("soon...", "soon...", function()
    print("komingsoon")
end)
HubSection:NewButton("soon...", "soon...", function()
    print("komingsoon")
end)
--more soon








-- game skripts
local Games = Window:NewTab("Games")
local GamesSection = Games:NewSection("Games")

GamesSection:NewLabel("🎃🎃🎃FREE UGC SKRIPTS🎃🎃🎃***")
GamesSection:NewLabel("Tower of Madness")
GamesSection:NewButton("[🎃] tower of madness", "free ugx", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0TowerMadness'))()
    --tower of madness
end)
GamesSection:NewButton("teleport to game", "towerofmadness", function()
    local PlaceId = 6470944645 -- tower of madness

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("Karry A Friend")
GamesSection:NewButton("karry a friend (teamwork obby)", "free ugx", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0Carry"))()
    --karry a friend-
end)
GamesSection:NewButton("teleport to game", "karry deeznuts", function()
    local PlaceId = 14448662003 -- karry a friend

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("[🎃] Pull A Sword")
GamesSection:NewButton("pull a sword", "free ugx", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0PullaSword",true))()
    --pull a sword
end)
GamesSection:NewButton("teleport to game", "pull a sword", function()
    local PlaceId = 13827198708 -- pull a sword

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("[🎃] Harmony Hills RP")
GamesSection:NewButton("harmony Hills RP", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0Harmony",true))()
    --harmony hills RP
end)
GamesSection:NewButton("teleport to game", "harmony hills rp", function()
    local PlaceId = 11707114324 -- harmony hills rp

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)

end)

GamesSection:NewLabel("Mining Faktory Tykoon")
GamesSection:NewButton("mining faktory tykoon (INSTANT)", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0MiningFactory",true))()
    --mining faktory tykoon(instant)
end)
GamesSection:NewButton("teleport to game", "miningfaktory", function()
    local PlaceId = 12717051222 -- mining faktory tykoon

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("[🎃] Driving Empire")
GamesSection:NewButton("driving empire", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0DrivingEmpire",true))()
    --driving empire
end)
GamesSection:NewButton("teleport to game", "drivingempire", function()
    local PlaceId = 3351674303 -- driving empire

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("[🎃] Halloween Hunt")
GamesSection:NewButton("Halloween hunt👻", "free ugx", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/BaconBossScript/HalloweenHunt/main/HalloweenHunt"))()
    --halloween hunt
end)
GamesSection:NewButton("teleport to game", "halloweenHunt", function()
    local PlaceId = 14460259920 -- halloween hunt

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("Barrel Raxe")
GamesSection:NewButton("barrell raxe", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0Barrel",true))()
    --barrel raxe
end)
GamesSection:NewButton("teleport to game", "barrelraxe", function()
    local PlaceId = 14947359762 -- barrell raxe

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("[🎃NEW] Rainbow Friends")
GamesSection:NewButton("Rainbow Friends Morphs", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0Rainbow",true))()
    --Rainbow friends morphs
end)
GamesSection:NewButton("teleport to game", "rainbowfriends", function()
    local PlaceId = 10132505018 -- rainbow friends

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("Sumo Simulator")
GamesSection:NewButton("sumo simulator", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0Sumo",true))()
    --sumo simulator
end)
GamesSection:NewButton("teleport to game", "sumosimulator", function()
    local PlaceId = 14021953565 -- sumo sim

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("iHeartLand Temple of Sound")
GamesSection:NewButton("iheartland - Temple of Sound", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0iHeartLand",true))()
    --iheartland Temple of Sound
end)
GamesSection:NewButton("teleport to game", "iheartlandtempleofsound", function()
    local PlaceId = 9524757503 -- iheart land temple of sound

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("AFK FOR UGC")
GamesSection:NewButton("AFK for ugc", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0UGCAFK",true))()
    --AFK for ugc
end)
GamesSection:NewButton("teleport to game", "afkforugc", function()
    local PlaceId = 14776528572 -- afk for ugc

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

GamesSection:NewLabel("Dont Move")
GamesSection:NewButton("dont move", "free ugx", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0DontMove",true))()
    --dontmove1
end)
GamesSection:NewButton("dont move - skript 2", "dontmove", function()
    loadstring(game:HttpGet("https://github.com/ToraIsMe/ToraIsMe/raw/main/0Don'tMove",true))()
    --dontmove2
end)
GamesSection:NewButton("teleport to game", "dontmove", function()
    local PlaceId = 14620329550 -- dontmove 1

    game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)


GamesSection:NewLabel("[🖍️Find The Markers🖍️]")
GamesSection:NewButton("ESP & marker traxer", "easy tp to random marker", function()loadstring(game:HttpGet('https://pastebin.com/raw/7gu2ztpP'))()
end)
GamesSection:NewLabel("[❌🚪50/50 Pixk A Door🚪✅]")
GamesSection:NewButton("50/50 Pixk A Door", "reveals all doors in lime green", function()
  getgenv().Door = true

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

local GamesSection = Games:NewSection("[🗡️KAT🗡️]")

GamesSection:NewButton("KAT GUI", "esp,spam shoot (aimbot💻)", function()--kat gui
loadstring(game:HttpGet("https://pastebin.com/raw/78kG7trR"))()
end)

GamesSection:NewButton("OP Darkyyware", "OP skript for KAT",
function()-- KAT darkyyware
loadstring(game:HttpGet("https://raw.githubusercontent.com/AndrewDarkyy/NOWAY/main/darkyyware.lua"))()
end)
GamesSection:NewButton("REALKING KAT GUI", "OP skript for KAT",
function()-- REALKING KAT GUI
loadstring(game:HttpGet('https://raw.githubusercontent.com/zReal-King/Knife-Ability-Test/main/Gui'))()
end)
GamesSection:NewButton("Kopy >REALKING KAT GUI< 🔑", "key: 7hFUsGVXaQ73mxgNjQJZjp4SEXy9yPdzN4bH38PdrYNBTkQw3nH2Y2mqKFcFkS52", function()
setclipboard("7hFUsGVXaQ73mxgNjQJZjp4SEXy9yPdzN4bH38PdrYNBTkQw3nH2Y2mqKFcFkS52")
end)
GamesSection:NewButton("Aimbot(KAT)", "shoots nearest player",
function()-- kat aimbot
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-AIMBOT-SKRIPT-6783"))()
end)

local GamesSection = Games:NewSection("[🏚️🧱Da Hood🧱🏚️]")

GamesSection:NewButton("DaHood Reborn Aim", "dahood aimloxk", function()loadstring(game:HttpGet("https://pastebin.com/raw/iNd3xTPv"))()
end)
GamesSection:NewButton("Da Hood GUI 1", "DA HOOD is kinda good", function()
 loadstring(game:HttpGet('https://pastebin.com/raw/ZCiS8jSd'))()
end)

GamesSection:NewButton("DaHood GUI 2", "New GUI", function()
 loadstring(game:HttpGet(("https://raw.githubusercontent.com/SoftVortex/.../main/....."),true))()
end)
GamesSection:NewButton("Da Hood GUI 3", "DaHood Evil", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Impulseonyoutube/scripts/main/dahood"))()
end)
GamesSection:NewButton("Da Hood GUI 4", "DaHood Evil", function()
 loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\71\97\109\101\114\69\109\105\108\105\97\110\111\70\70\47\116\114\105\112\95\47\109\97\105\110\47\72\117\98\10",true))()
end)
GamesSection:NewButton("Da Hood Gui 5", "Dahood idk", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Impulseonyoutube/scripts/main/dahood"))()
end)
GamesSection:NewButton("Da Hood GodMode", "invinxibility", function()
p = game.Players.LocalPlayer
ch = p.Character

ch.BodyEffects.Dead:Destroy()
end)
GamesSection:NewButton("DaHood Silent Aim", "silent aim", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Impulseonyoutube/scripts/main/dahood"))()
end)
GamesSection:NewButton("DaHood Gui 6(New and Op)", "So many skripts", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/SpaceYes/Lua/Main/DaHood.Lua'))()
end)
GamesSection:NewButton("DaHood Gui 7(New)", "gai", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BalligusapoTT/BalligusapoTT/main/UntitledhoodGui"))()
end)
GamesSection:NewButton("Aimloxk (use Q tool)", "Q tool", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/DYZ2fug0",true))()
end)

GamesSection:NewButton("any tool -dahood", "any tool pixker for dahood", function()
  loadstring(game:HttpGet("https://pastecode.dev/raw/7PZTHFQZwr/DaHoodanytool",true))()
end)


local GamesSection = Games:NewSection("[🥞Pankake Empire Tykoon🥞]")
GamesSection:NewButton("Pankake Empire Tower", "yum🥞🥞🥞", function()
-- pankake tora
loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0pancake", true))()
end)

--XHAOS GAME
GamesSection:NewLabel("[⚔️Chaos⚔️]")
GamesSection:NewButton("KILL PLAYER FROM FAR V2", "selekt a player and put kill", function()--xhaos kill
  loadstring(game:HttpGet("https://pastebin.com/raw/W9SYMbiw"))()
end)


GamesSection:NewLabel("[🏏Blade Ball☄️]")

GamesSection:NewButton("Ln Hub", "lm hub v2 bladeball V2", function()--Ln Hub (blade ball)

  loadstring(game:HttpGet('https://raw.githubusercontent.com/No6No6No7yt/Lumin-Hub/main/BladeV2.lua'))();
end)
GamesSection:NewButton("AUTO PARRY", "auto parry for bladeball", function()_G.Config = {
    MinDistance = 10,
    DelBallSpeed = 3,
  }

  loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
end)
GamesSection:NewButton("AUTO BLOXK", "auto bloxk for bladeball", function()--autoblox
  loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/AutoBlock"))()
end)
GamesSection:NewButton("Insurgent Hub", "bladeball", function()--insurgenthub
  loadstring(game:HttpGet('https://raw.githubusercontent.com/InsurgenceHub/IncurgenceHub.github.io/main/InsurgentHubOfficial'))()
end)
GamesSection:NewButton("Lumin Hub V4", "bladeball", function()--luminhubv4
  loadstring(game:HttpGet('https://raw.githubusercontent.com/No6No6No7yt/Lumin-Hub/main/BladeV4.lua'))();
end)
GamesSection:NewButton("Baller Hub", "bladeball", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/Blade231/main/Baller"))()
end)
GamesSection:NewButton("Bladeball Hub", "bladeball", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/SourceLua/main/Blade_Ball.lua"))()
end)
GamesSection:NewButton("R3THPRIV Hub", "bladeball", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/R3TH-PRIV/R3THPRIV/main/loader.lua'))()
end)
GamesSection:NewButton("ImNotFat Hub", "bladeball", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/ImNotFatBitch/LoaderScripts/main/LoaderScripts"))()
end)
GamesSection:NewButton("MalixiousDev Hub", "bladeball", function()
  loadstring(game:HttpGet(('https://raw.githubusercontent.com/malicious-dev/RobloxScripting/main/bladeball.lua'),true))()
end)

--BROOKHAVEN
GamesSection:NewLabel("[🏡Brookhaven RP🏡]")
--BUTTONS
GamesSection:NewButton("Juanko Hub", "skripthub by juanko", function()loadstring(game:HttpGet("https://pastebin.com/raw/qBHKy3Ss"))()
end)
GamesSection:NewLabel("[🏡Brookhaven RP🏡]")
--BUTTONS
GamesSection:NewButton("Brookhaven 1", "brookhaven skript alexh01", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Alech01/Scripts-Randoms/main/Brook%20Haven%20Script"))()
  -- Brookhaven skript 
end)
GamesSection:NewButton("smilex2222 Brookhaven ", "infohere", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/smilex2222/script/main/Brookhavenscript.lua'))()
  -- Brookhaven skript 2
end)
GamesSection:NewButton("BOTSK HUB", "botsk hub", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/BOTSKHUB/Brookhaven-SKPC/main/si"))()
  -- Brookhaven skript 3
end)
GamesSection:NewButton("Brookhaven  rp v1", "v1 brookhsven skript", function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Brookhaven-rp-v1-7505"))()
  -- Brookhaven skript 4
end)
GamesSection:NewButton("Pormans Brookhaven", "V1 keyless", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/pormansutility/PormansBrookhaven/main/BrookhavenV1Keyless"))()
  -- Brookhaven skript 5
end)
GamesSection:NewButton("BrookHaven skript", "BH RP", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
  -- Brookhaven skript 6
end)
GamesSection:NewButton("BrookHaven RP xhat bypasser", "bypasst xhat only for BH", function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-chatbypasser-6851"))()
  -- Brookhaven xhatbypasser skript
end)
GamesSection:NewButton("REDz Hub", "redz for bh", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
  -- Brookhaven  7
end)
GamesSection:NewButton("❄️Ixe Hub❄️", "brookHaven ixehub", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
  -- ixe hub skript
end)



--BLOXFRUIT
GamesSection:NewLabel("[🍒🍊BLOX FRUITS🍇🍎]")
GamesSection:NewButton("SepuhHub", "bloxfruit", function()loadstring(game:HttpGet("https://isnahamzahpastebin.tech/sepuh/puh_007.lua"))()
end)
GamesSection:NewButton("MTriet Hub", "bloxfruits", function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
end)

GamesSection:NewLabel("[👧🏽Rate My Avatar👦🏼]")

GamesSection:NewButton("Rate my avatar 1", "rma1", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/xDvJRDzg",true))()
end)


local GamesSection = Games:NewSection("[T-TITANS BATTLEGROUNDS🦸‍♀️🦹🏿‍♂️]")

GamesSection:NewButton("T-TITANS BATTEGROUNDS OP GUI", "no kooldown blah blah", function()pcall(function()

loadstring(game:HttpGet("https://roflux.net/scripts/games/" .. tostring(game.PlaceId) .. ".lua"))()
end)
end)

local GamesSection = Games:NewSection("[🐕Pet Empire Tykoon🐕]")

GamesSection:NewButton("Auto Kollekt, Auto Press, etx.", "🐶🐱🐕🐰🐈🐹🐇", function()-- petempire toraisme
loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe2/ToraIsMe2/main/0pettycoon", true))()
end)

local GamesSection = Games:NewSection("[Survive & Kill The Killers in AREA 51👽🛸]")

GamesSection:NewButton("Raygun Tp, 99999 Ammo", "press the gun off and on to get 99999 ammo", function()loadstring(game:HttpGet("https://pastebin.com/raw/tCxvzGXi"))()
end)

local GamesSection = Games:NewSection("[🧟‍♂️Zombie Attaxk🧟‍♂️]")

GamesSection:NewButton("Autofarm, All guns/knives, etx.", "my zombie atk gui", function()loadstring(game:HttpGet("https://pastebin.com/raw/fzxqESwF"))()
end)

local GamesSection = Games:NewSection("[🌈Rainbow Friends 2🎭]")

GamesSection:NewButton("OP Rainbow Friends GUI", "best rainbow friends skript", function()loadstring(game:HttpGet('https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0rainbow'))()
end)

local GamesSection = Games:NewSection("[🐇Adopt Me🐴]")

GamesSection:NewButton("Fly Ride Pets", "fly ability for all pets", function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/scripts/main/adoptmegui1'),true))()
end)

local GamesSection = Games:NewSection("[💪🏽Strongman Simulator🏋🏾]")
GamesSection:NewButton("Strongman Simulator Autofarm GUI", "gui",
function()-- strongman simulator 
loadstring(game:HttpGet("https://raw.githubusercontent.com/ProjectLightningDev/Project-Lightning-Loader/main/Loader.Lua"))()
end)

local GamesSection = Games:NewSection("[⛓️Prison Life🚔]")

GamesSection:NewButton("Tiger Admin", "admin kommands, kmdlist",
function()loadstring(game:HttpGet('https://raw.githubusercontent.com/H17S32/Tiger_Admin/main/Script'))()
end)

GamesSection:NewButton("STEAL ALL TOOLS", "works if player has tools (tools=items)",
function()for i,v in pairs (game.Players:GetChildren()) do
wait()
for i,b in pairs (v.Backpack:GetChildren()) do
b.Parent = game.Players.LocalPlayer.Backpack
end
end
end)

GamesSection:NewButton("Tiger Admin (REVAMPED)", "tiger admin revamp",
function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-TIGER-ADMIN-REVAMPED-7593"))()
  --Tiger admin revamped new version
end)

GamesSection:NewButton("Prison life admin hub", "adminHub",
function()
    loadstring(game:HttpGet("https://pastebin.com/raw/GzeWWPWN"))()
    -- Prison life admin hub
end)

GamesSection:NewButton("Juanko Prison Life Admin Hub", "request by emil", function()
--[[
Juanko prison life admin hub only games prison life
]]
loadstring(game:HttpGet("https://pastebin.com/raw/0Jyaa9aQ"))()
end)

GamesSection:NewButton("Version Life hub", "request by emil", function()
--[[
version life hub for prisonlife
]]
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Berliandakhensy/Version/main/version%20life.lua.txt"))()
end)

GamesSection:NewButton("Nexus Hub", "hub",
function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/GwnStefano/NexusHub/main/Main", true))()
  --Nexus hub for prison life game
end)

GamesSection:NewButton("Synix Beta Hub", "hub",
function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/GwnStefano/NexusHub/main/Main", true))()
  --Nexus hub for prison life game
end)

GamesSection:NewButton("Remove Trees", "self explanatory", function()
--[[
delete trees
]]
game:GetService("Workspace").Trees:Destroy()
end)

GamesSection:NewButton("FE sound for prison life", "fe sound", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/SmartModBoy/script4/main/prisonsound", true))()
  --fe sound for prison life game
end)

GamesSection:NewButton("Mobile Paxks for prison life", "paxks", function()
  loadstring(game:HttpGet('https://freenote.biz/raw/ZcYw0XR8lW'))()
  --Mobile paxks
end)

GamesSection:NewButton("prison life 1", "skript", function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-Roblox-script-8414"))()
  --Prison life 1 
end)

GamesSection:NewButton("prison life 2", "skript", function()
  loadstring(game:HttpGet('https://paste.website/p/96d68817-3f1e-4fef-a8b8-9aafdc810329.txt'))()
  --Prison life 2
end)

GamesSection:NewButton("prison life 3", "skript", function()
  loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\103\48\48\108\88\112\108\111\105\116\101\114\47\103\48\48\108\88\112\108\111\105\116\101\114\47\109\97\105\110\47\70\101\37\50\48\98\121\112\97\115\115\34\44\32\116\114\117\101\41\41\40\41\10")()
  --Prison life 3
end)

GamesSection:NewButton("prison life 4", "skript", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/xgJ27vLc"))()
  --Prison life 4
end)

GamesSection:NewButton("prison life 5 - SSSWWW222", "skript", function()
  loadstring(game:HttpGet(('https://raw.githubusercontent.com/zeuise0002/SSSWWW222/main/README.md'),true))()
  --Prison life 5
end)

GamesSection:NewButton("prison life 6 gui", "gui for prisonlife", function()
  loadstring(game:HttpGet("https://pastebin.com/3caDghrg"))();
  --Prison life 6
end)

GamesSection:NewButton("prison life 7 - PixelLoxkers", "gui for prisonlife", function()
  loadstring(game:HttpGet('https://raw.githubusercontent.com/PixelLockers/Roblox-Scripts----/main/Prison%20Life-Script%20(v1)', true))()
  --Prison life 7
end)

GamesSection:NewButton("PRISONWARE v1.3", "gui for prisonlife", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))();
  --Prison life 8
end)

GamesSection:NewButton("TeddyHub", "gui for prisonlife", function()
  loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-(Cars-fixed!)-Prison-life-teddy-hub-2451"))()
  --Prison life 9
end)

GamesSection:NewButton("prison life 10 gui", "gui for prisonlife idk", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/mHfK0Xk4", true))()
  --Prison life 10
end)


local GamesSection = Games:NewSection("[🏃🏽‍♂️💨Flee The Faxility💻]")

GamesSection:NewButton("AutoHaxk,ESP & more", "ftf gui",
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/LeviTheOtaku/roblox-scripts/main/FTFHAX.lua",true))()
end)

local GamesSection = Games:NewSection("[❓Murder Mystery 2🔪]")

GamesSection:NewButton("MM2 GUI (New)", "esp,see murderer&more",
function()loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Drifter0507/GUIS/main/MURDER%20MYSTERY%202", true))();
end)

GamesSection:NewButton("MM2 Admin Panel", "esp blah blah more",
function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
end)

GamesSection:NewButton("OP MM2 GUI 2", "best mm2 skript",
function()-- MURDER MYSTERY 2 kavoui
loadstring(game:HttpGet("https://raw.githubusercontent.com/Amenteso/robloxscripts/main/Key.lua",true))()
end)

GamesSection:NewButton("Kopy >OP MM2 GUI 2< 🔑", "key: mTAgLLFQJazwRWGh",
function()setclipboard("mTAgLLFQJazwRWGh")
end)

GamesSection:NewButton("Symphony Hub (OP!)", "op asf",
function()
  local a,b,c,d=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,"https://itsjidy.github.io/SymphonyHub/Loader.html"c(a and b, "your exekutor is not supported")a(b({Url=d,Method="GET"}).Body)()
end)

local GamesSection = Games:NewSection("[FREE ADMIN]")

GamesSection:NewButton("Fedatorum Admin Abuser", "only works in freeadmin games",
function()-- fedatorum admin abuser
loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/showcases/main/fedoratumadmin",true))()
end)

local GamesSection = Games:NewSection("🗼Tower Of Hell🗼")

GamesSection:NewButton("ToH Admin", "its only admin kommands", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/TwomadJR/nto/main/admiin"))()
end)

GamesSection:NewButton("ToH GUI 1", "so Op for TOH", function()
  loadstring(game:HttpGet('https://pastebin.com/raw/BbVHjH56'))()
end)

GamesSection:NewButton("ToH Gui 2", "2", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/garfield%20hub", true))()
end)

GamesSection:NewButton("ToH Gui 3", "gui3", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/03koios/TowerOfHell/main/README.md"))()
end)

GamesSection:NewButton("ToH Gui 4", "toh gui4", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/iiProductionz/Floater-Scripts/main/WaifuEdition/Tower%20Of%20Hell"))()
end)

GamesSection:NewLabel("🏈Football Fusion🏈")
GamesSection:NewButton("Football Fusion GUI 1", "havent tested or tried this skript so idk", function()
--football fusion 1
loadstring(game:HttpGet('https://raw.githubusercontent.com/1x2x3/Kanye/main/loadstring.lua'))();
end)

GamesSection:NewButton("Football Fusion GUI 2", "idk gui", function()
--football fusion 2
loadstring(game:HttpGet("https://wiihub.wiigen.net/loaderfree.lua", true))()
end)

GamesSection:NewButton("Football Fusion GUI 3", "ff gui idk", function()
  --football fusion 3
loadstring(game:HttpGet('https://pastebin.com/raw/94bSvnqL'))()
end)

GamesSection:NewLabel("🤑Millionaire Empire Tykoon💵")
GamesSection:NewButton("Millionaire empire gui", "skript", function()
-- millionaire empire tykoon
loadstring(game:HttpGet("https://raw.githubusercontent.com/Lucasfin000/SpaceHub/main/spacvehubloader"))()
end)

GamesSection:NewLabel("🫗Slime Tower Tykoon🫗")
GamesSection:NewButton("slime tower 1", "slimetower skript", function()
-- slime tower tykoon
loadstring(game:HttpGet("https://raw.githubusercontent.com/XRoLLu/Rolly_Hub/main/open-source-trash-loader.exe.yeah"))()
end)

GamesSection:NewLabel("🏃🏽‍♂️Sonik Speed Simulator🏃🏽‍♂️")
GamesSection:NewButton("Sonik Speed Sim gui", "sonikspeedsim gui",
function()
  -- sonik speed sim
loadstring(game:HttpGet('https://raw.githubusercontent.com/zReal-King/King-Hub-v2/main/Loader.lua'))()
end)

GamesSection:NewLabel("🛒Kart Ride Into Rdite🛒")
GamesSection:NewButton("kart ride into rdite(fun gui)", "finish blah blah",
function()-- kart ride into rdite
loadstring(game:HttpGet("https://raw.githubusercontent.com/Lucasfin000/SpaceHub/main/spacvehubloader"))()
end)

GamesSection:NewLabel("🪦All Of Us Are Dead🪦")
GamesSection:NewButton("All of us are dead 1", "something",
function()-- all of us are dead
loadstring(game:HttpGet(('https://raw.githubusercontent.com/zeuise0002/SSSWWW222/main/README.md'),true))()
end)

GamesSection:NewLabel("Pop It Trading")
GamesSection:NewButton("pop it trading gui", "POP IT TRADING DUM*A$$",
function()-- pop it trading
loadstring(game:HttpGet("https://raw.githubusercontent.com/iShield2005/scripts/master/shieldhubloader2"))()
end)

GamesSection:NewLabel("👻🚪DOORS🚪👻")
GamesSection:NewButton("Doors -Awesome Hub gui", "awesomehubgui",
function()-- doors awesome skript
loadstring(game:HttpGet("https://rawscripts.net/raw/DOORS-awesome-script-11450"))()
end)

GamesSection:NewButton("Doors - Toosiwhip hub V6 ", "toosiwhiphub",
function()-- doors toosiwhip v6
loadstring(game:HttpGet('https://raw.githubusercontent.com/toosiwhip/statue-v6/main/doors.lua'))()
end)

GamesSection:NewButton("Doors - Shadowhub", "shadowskripts",
function()-- doors shadowskript
loadstring(game:HttpGet('https://raw.githubusercontent.com/ShadowScripts4Roblox/PROTECTEDLUA/main/Scripts/DOORS/Loader52.lua'))()
end)

GamesSection:NewLabel("❌Impossible Glass Bridge Obby✅")
GamesSection:NewButton("Reveal Tiles", "reveal tiles blahbla",
function()-- impossible glass bridge obby
loadstring(game:HttpGet("https://github.com/KhSaeed90/Roblox/raw/workspace/ImpossibleGlassBridge"))()
end)

GamesSection:NewLabel("😡Stairs Of Rage😡")
GamesSection:NewButton("Stairs of rage 1", "let them stay mad",
function()
  -- stairs of rage
loadstring(game:HttpGet("https://raw.githubusercontent.com/WinterDinder/Stairs-Of-Rage/main/Main", true))()
end)

GamesSection:NewLabel("🏃🏽‍♂️🚓Barrys Prison Run👮🏼‍♂️🚔")
GamesSection:NewButton("Barrys prison run gui", "run b run",
function()-- barrys prison run
loadstring(game:HttpGet("https://github.com/KhSaeed90/Roblox/raw/workspace/Barry'sPrisonRun"))()
end)

GamesSection:NewLabel("🎹Piano Player🎹")
GamesSection:NewButton("Auto Piano Player", "auto piano",
function()
  -- piano player
loadstring(game:HttpGet("https://raw.githubusercontent.com/Madness676/3.2Lol/main/AutoPiano3-2.lua", true))()
end)

GamesSection:NewLabel("🙈Extreme Hide N Seek🙈")
GamesSection:NewButton("Extreme Hide n Seek", "idk",
function()-- extreme hide n seek
loadstring(game:HttpGet('https://pastebin.com/raw/HAgidzUN'))()
end)

GamesSection:NewLabel("👧🏽Rate My Avatar👦🏽")
GamesSection:NewButton("Rate My Avatar 1", "idk",
function()
  -- rate my avatar
loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

local GamesSection = Games:NewSection("🦸Anime Dimensions")

GamesSection:NewButton("Anime Dimensions 1", "Different anime lol", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/TheWitch-BirdHub/BirdHubv0.1/main/load"))()
end)

GamesSection:NewButton("Anime Dimension 2", "Anime wow im a fan lol", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/ghost-home/public/main/AnimeGhost.lua', true))()
end)

local GamesSection = Games:NewSection("No Skope Sniper")

GamesSection:NewButton("Op Silent Aim", "Well its not silent lol", function()
    getgenv().Settings = {

 Fov = 150,

 Hitbox = "Head",

 FovCircle = true,

}



loadstring(game:HttpGet("https://raw.githubusercontent.com/WetCheezit/Releases/main/No-Scope-Arcade/Silent%20aim.lua"))()
end)

local GamesSection = Games:NewSection("🚢Build A Boat🚢")

GamesSection:NewButton("Build a Boat 1", "havent played", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-HUB/HUB/main/Script"))()
end)

GamesSection:NewButton("Build a Boat 2", "havent play", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()
end)

GamesSection:NewButton("Build a Boat 3", "Dino-Hub", function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/SandaFrosty/Dino-Script/main/Build-Boat-For-Treasure"))()
end)

GamesSection:NewButton("Build a Boat 4", "i dont play it so idk", function()
_G.autofarm = true loadstring(game:HttpGet('https://gist.githubusercontent.com/cod2rx/d2a7e436d3af135d787529141e6485cc/raw/5bb4df0a94b0a3cf06f0c87a25cb6859e56d23e3/BABFT%2520Autofarm.lua'))()
end)

GamesSection:NewButton("Build a Boat 5", "BAB5 gui", function()
_G.Color = Color3.fromRGB(255, 255, 255)
loadstring(game:HttpGet"https://rawscripts.net/raw/SAZA-HUB_496")()
end)

local GamesSection = Games:NewSection("💪🏽💥Musxle Legend💥💪🏽")

GamesSection:NewButton("Musxle Lengend GUI 1", "op", function()
 loadstring(game:HttpGet('https://raw.githubusercontent.com/jynzl/main/main/Musclas%20Legenos.lua'))()
end)

GamesSection:NewButton("Musxle legend Gui 2", "yea", function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/harisiskandar178/Roblox-Script/main/Muscle%20Legend"))()
end)

local GamesSection = Games:NewSection("🥷Ninja Legend🥷")

GamesSection:NewButton("Ninja Legend GUI 1", "its old af", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/1"))()
end)

GamesSection:NewButton("Ninja Legend GUI 2", "its OP but its old", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/StormSKz12/StirkeHub1/main/Gameincluded"))()
end)

local GamesSection = Games:NewSection("🥺💰Pls Donate💰🥺")

GamesSection:NewButton("Pls Donate Gui 1", "pls", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/PLEASE-DONATE-NEW-GUI-/main/METAB"))();
end)

GamesSection:NewButton("Pls Donate Gui 2", " Poor", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/PLEASE-DONATE-BOOTH-/main/METAB"))()
end)

local GamesSection = Games:NewSection("One Piexe")

GamesSection:NewButton("One piexe 1", "Luffy,Zoro,Sanji,Usopp", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/32"))()
end)

GamesSection:NewButton("One Piexe 2", "Pirate king", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/Urbanstorms/Cool-things/main/A%200ne%20Piece%20Game.lua'),true))()
end)

local GamesSection = Games:NewSection("Raise A Floppa")

GamesSection:NewButton("Raise a Floppa Gui 1", "Feed kat", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/SunkenMuch/Soggyware/main/Main',true))()
end)

local GamesSection = Games:NewSection("Shrek in Baxkroom")

GamesSection:NewButton("Shrek in Baxkroom Gui 1", "Shrekkkk", function()
loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\110\106\120\66\100\102\67\76\10"))()
end)

local GamesSection = Games:NewSection("Starving Artist")

GamesSection:NewButton("Starving Artist Kopy", "wow u bad at art lol", function()
Settings = {
  Timer = false -- false if You Dont Wanna Timer --
}

loadstring(game:HttpGet(('https://raw.githubusercontent.com/anisnouacer1/My-Roblox-Scripts/main/Starving%20Artists.lua')))()
end)


local GamesSection = Games:NewSection("Be A parkour Ninja")

GamesSection:NewButton("Be a Parkour Gui 1", "op", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Min1273/n-to/main/README.md"))()
end)



--// FE SKRIPTS \\--

local Fe = Window:NewTab("FE")
local FeSection = Fe:NewSection("FE Skripts")

FeSection:NewButton("FE Stop Time", "freeze in mid air or whatever", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/creepstu/fuzzy-octo-giggle/main/Source'))()
end)

FeSection:NewButton("FE Fish", "(need hat) Parrot Fishfaxe", function()
-- fe fish
loadstring(game:HttpGet(('https://pastefy.app/yrp6En96/raw'),true))()
end)

FeSection:NewButton("FE Ragdoll Yourself", "reset or die to disable", function()loadstring(game:HttpGet("https://pastebin.com/raw/VY5d58xz"))()
end)

FeSection:NewButton("FE Korblox", "need korblox rekolor for 65 robux, R15", function()
loadstring(game:HttpGet("https://pastebin.com/raw/0NzfiZJn"))()
end)

FeSection:NewButton("FE Vehikle Fly", "flying kar gui", function()
loadstring(game:HttpGet("https://pastebin.com/raw/MHE1cbWF"))()
end)

FeSection:NewButton("FE Baxkflip/Frontflip", "baxk and frontflip", function()
-- fe bk & front
loadstring(game:HttpGet(('https://pastefy.app/yrp6En96/raw'),true))()
end)

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

FeSection:NewButton("FE 2007 animation", "baxk to the old days", function()
loadstring(game:HttpGet("https://pastebin.com/raw/8gi79AtK"))()
end)

FeSection:NewButton("FE fly any hat like a dragon", "use keybind stroke to move", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BidoSkinsYT/BidoSkinsYT/main/Fe%20hat%20Dragon"))()
end)

FeSection:NewButton("FE Headless", "yellow grey", function()
loadstring(game:HttpGet("https://pastebin.com/raw/Fp0GgURD"))()
end)

FeSection:NewButton("FE WAR ENDER", "warendergod", function()
loadstring(game:HttpGet("https://textbin.net/raw/nos6oilby7"))()
end)

FeSection:NewButton("FE Krazy", "by dark", function()
loadstring(game:HttpGet("https://textbin.net/raw/rdssq0b2em"))()
end)

FeSection:NewButton("FE Kreepy Krawler", "turns u into kreepy krawler", function()
loadstring(game:HttpGet("https://pastebin.com/raw/rzcFPsLn"))()
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

FeSection:NewButton("FE Message Art", "turn text into art", function()
loadstring(game:HttpGet("https://textbin.net/raw/hmtw3zllmp",true))()
end)

FeSection:NewButton("FE Invisible & Teleport GUI", "any game *op*", function()-- FE Invisible GUI & Teleport R15/R6 | ANY GAME *OP*
loadstring(game:HttpGet('https://raw.githubusercontent.com/0Ben1/fe./dbb6ce6f6cee4f7a5c9e20d7b88e83db2a93bf25/Invisible%20GUI'))()
end)


--// more skripts \\--
local ex = Window:NewTab("Teleports & Extras")

local exSection = ex:NewSection("99% fail impossible obby teleportation")

exSection:NewButton("Teleport to Treasure", "teleport to the xhest",
function()-- teleport to xhest
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-911.98291015625, 2005.8095703125, -149.64857482910156)
end)

exSection:NewButton("Teleport to Finish", "teleport to the xhest",
function()-- teleport behind xhest
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-921.2446899414062, 1995.87255859375, -150.1106719970703)
end)

exSection:NewButton("Teleport to Danger Zone (tile 60)", "teleport to dz",
function()-- teleport to dzaktually
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-593.0650634765625, 1993.9764404296875,
-153.38563537597656)
end)--tptodz

exSection:NewButton("Teleport to Start", "teleport to beginning",
function()Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(253.8822479248047, 1995.86083984375, -149.1727752685547)
end)--tptostart

exSection:NewButton("Teleport to Winners Room", "teleport to the golden room",
function()-- teleport to winning room
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(314.3387451171875, 17002.197265625, 202.53802490234375)
end)

exSection:NewButton("Teleport to Offixe Seat", "sits u in the offixe seat",
function()-- sit in the offixe
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(259.6474304199219, 17004.259765625,
162.38287353515625)
  -- sit while tp
game.Players.LocalPlayer.Character.Humanoid.Sit = true
end)

exSection:NewButton("Teleport to Hidden Area", "teleport to unknown area",
function()-- teleport to hidden 99
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(269.36907958984375, 17024.74609375,
139.19142150878906)
end)
--[endTP]--

exSection:NewLabel("Teleport To Game")
exSection:NewLabel("ask for more game teleports if your game is not here🍭")

exSection:NewButton("Teleport to 99% fail impossible obby", "no info", function()-- tp to 99
local PlaceId = 7584496019 -- gameID

game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

exSection:NewButton("Teleport to Zombie Attaxk", "no info", function()-- tp to zombie atk
local PlaceId = 1240123653 -- gameID

game:GetService("TeleportService"):Teleport(PlaceId, game:GetService("Players").LocalPlayer)
end)

local exSection = ex:NewSection("Troll")

exSection:NewButton("Non-FE Hub (old)", "some dont work", function()-- NONFE HUB
loadstring(game:HttpGet("https://pastebin.com/raw/mjPzCChH"))()
end)

exSection:NewButton("Klone script", "klones ur avatar not fe", function()
  loadstring(game:GetObjects('rbxassetid://7339698872')[1].Source)()
end)

exSection:NewButton("Fake kixk", "when people leave it makes them think you kixk them", function()
  loadstring(game:HttpGet('https://pastebin.com/raw/9H4EGzHg'))()
end)

exSection:NewButton("Loop Fling all", "automatikally flings people", function()
  loadstring(game:HttpGet('https://github.com/DigitalityScripts/roblox-scripts/raw/main/loop%20fling%20all'))()
end)


exSection:NewLabel("Weapons")

exSection:NewButton("Klumsy Gunner", "kool", function()-- klumsy gunner
loadstring(game:HttpGet("https://pastebin.com/raw/VdfTg8Rm"))()
end)

exSection:NewButton("Army Gunner", "🪖", function()-- army gunner
loadstring(game:HttpGet("https://pastebin.com/raw/6yf2cDfG"))()
end)

exSection:NewButton("Annoying Dual Pistols", "annoying", function()-- annoying dualpistols
loadstring(game:HttpGet("https://pastebin.com/raw/vWMd3ErY"))()
end)

exSection:NewButton("Alien Rifle", "annoying", function()-- huge double barrel alien rifle
loadstring(game:HttpGet("https://pastebin.com/raw/Ntq5K6gC"))()
end)

exSection:NewButton("Kamikaze", "timed bomb vest💣", function()-- kamikaze time bomb
loadstring(game:HttpGet("https://pastebin.com/raw/W34i4R8N"))()
end)

exSection:NewButton("Skull Smasher", "use mobile keyboard for movelist", function()-- SKULL SMASHER
loadstring(game:HttpGet("https://pastebin.com/raw/tnevgHaV"))()
end)

exSection:NewButton("Dark Edged Dual Blades", "use mobile keyboard for movelist", function()-- dark edged dual blades
loadstring(game:HttpGet("https://pastebin.com/raw/C334rgCT"))()
end)

exSection:NewButton("How to train your dragon", "gives u the pet from tbe movie", function()-- how to train your dragon pet
loadstring(game:HttpGet("https://pastebin.com/raw/iQZ9PJ4x"))()
end)

exSection:NewButton("Water Rings", "yes", function()-- water rings
loadstring(game:HttpGet("https://pastebin.com/raw/ijWxVpmf"))()
end)

exSection:NewButton("Dual Shield Lasers", "yes", function()-- dual dark shield lasers
loadstring(game:HttpGet("https://pastebin.com/raw/XpzHT9Fh"))()
end)

exSection:NewButton("Glowing Matrix Man", "yes", function()-- glowing matrix runner
loadstring(game:HttpGet("https://pastebin.com/raw/SwLFx5pw"))()
end)

exSection:NewButton("Robot Umbrella", "yes", function()-- dangerous umbrella
loadstring(game:HttpGet("https://pastebin.com/raw/V78KfuNf"))()
end)

exSection:NewButton("Invisible Laser Shooter", "kool", function()-- invisible laser shooter
loadstring(game:HttpGet("https://pastebin.com/raw/8Za5RNGH"))()
end)

exSection:NewButton("Dual Plasma Rifles", "yes", function()-- dual plasma shooter
loadstring(game:HttpGet("https://pastebin.com/raw/HEvM7C2t"))()
end)

exSection:NewButton("Shotgun", "partner", function()-- shotgun
loadstring(game:HttpGet("https://pastebin.com/raw/aMgrBsnQ"))()
end)

exSection:NewButton("Bomb Vest", "blow urself up", function()-- shotgun
loadstring(game:HttpGet("https://pastebin.com/raw/aMgrBsnQ"))()
end)

exSection:NewButton("The Big Blank R6", "blank r6 guy", function()-- Blank R6 guy
loadstring(game:HttpGet("https://pastebin.com/raw/pRETy1aA"))()
end)

exSection:NewButton("M86-SR Bipod", "snipeup", function()--M89-SR with Bipod
loadstring(game:HttpGet("https://pastebin.com/raw/4sBhUxS0"))()
end)

exSection:NewButton("Unknown Magik", "magixian", function()-- unknown Magik
loadstring(game:HttpGet("https://pastebin.com/raw/FSH0S4C2"))()
end)

exSection:NewButton("Invisible Weapon", "no info", function()-- invisible weapon
loadstring(game:HttpGet("https://pastebin.com/raw/GCUivFzA"))()
end)

exSection:NewButton("Speedy Winged Fighter", "no info", function()-- speedy winged fighter
loadstring(game:HttpGet("https://pastebin.com/raw/RKPE68Gz"))()
end)

exSection:NewButton("Dual M1911's", "no info", function()-- dual m1911
loadstring(game:HttpGet("https://pastebin.com/raw/N1Jr8BBd"))()
end)

exSection:NewButton("Winged Fire", "no info", function()-- Winged Fire
loadstring(game:HttpGet("https://pastebin.com/L0GbxNfL"))()
end)




-- Home.TabMy.Skrpts

local Home = Window:NewTab("Home")
local HomeSection = Home:NewSection("Home")

HomeSection:NewButton("🔎 Skript", "look up any skript", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/ScriptSearcher"))()
end)

HomeSection:NewTextBox("Walkspeed","xhanges the walkspeed", function(e)game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=e 
end)

HomeSection:NewTextBox("Jump Power","xhanges the jumppower", function(e)game.Players.LocalPlayer.Character.Humanoid.JumpHeight=e 
end)

HomeSection:NewButton("Reset Walkspeed","reset walkspeed to default", function()game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)

HomeSection:NewButton("Reset Walkspeed/Jumppower", "resets Walkspeed and jumpPower to default", function()
  game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
  game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)

HomeSection:NewButton("Ping Kounter", "see ping", function()
loadstring(game:HttpGet("https://pastebin.com/raw/MvKKJ331"))()
end)
HomeSection:NewButton("Rejoin", "rejoins the same lobby",
function()--rejoin lobby
local ts = game:GetService("TeleportService")

local p = game:GetService("Players").LocalPlayer



ts:TeleportToPlaceInstance(game.PlaceId, game.JobId, p)
end)
HomeSection:NewButton("Server Hop", "leave the game",
function()
loadstring(game:HttpGet("https://pastebin.com/raw/KahMvMeh"))()
end)
HomeSection:NewButton("Join Lowest Player Server", "makes u join same game but lowest player",
function()loadstring(game:HttpGet("https://pastebin.com/raw/H0LwsNGc"))()
end)
HomeSection:NewButton("Exit", "leave the game",
function()game:Shutdown()
end)
HomeSection:NewButton("No Lib %FO", "nolib%", function()loadstring(game:HttpGet("https://pastebin.com/raw/2Vxg0a72"))()
end)
HomeSection:NewButton("Get Koords", "x,y,z finder say /console", function()print(Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position)
end)
HomeSection:NewButton("BaxkDoorFinder", "finds a baxkdoor for admin or additional skripts", function()
  loadstring(game:HttpGet(('https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua'),true))()
end)
HomeSection:NewButton("Harked Reborn V2 (leaked)", "only in sekret games", function()
  loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Harked-Skript-6804"))()
end)
HomeSection:NewButton("Anti AFK", "disables afk limit", function()
---- Roblox Anti Afk Script

wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti AFK Skript"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,370,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="made by lulaslollipop"
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Aktive"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="Roblox tried to kixk u but i kixked him instead"wait(2)ab.Text="Status : Aktive"end)
end)

HomeSection:NewButton("Dark Dex mobile", "darkdex for mobile", function()--dark dex mobile
getgenv().Key = "Bash"
loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3AIY%20Dex",true))()
end)

HomeSection:NewButton("FraktureSS", "my baxkdoor.exe serverside", function()--FRAKTURE SS
loadstring(game:HttpGet("https://raw.githubusercontent.com/L1ghtingBolt/FraktureSS/master/unobfuscated.lua"))()
end)

HomeSection:NewButton("Message Logs", "see xhatlogs gui", function()
  loadstring(game:GetObjects("rbxassetid://1295331911")[1].Source)()
end)

HomeSection:NewButton("Destroy toggle", "bye", function()--gui destroyer
  for i,v in pairs(game.CoreGui:GetDescendants()) do
   if v.Name == "ScreenGui" then
    v:Destroy()
   end
  end
end)





-- More.TabMy.Skrpts
local More = Window:NewTab("More")
local MoreSection = More:NewSection("more skripts koming soon...🍭")

MoreSection:NewButton("Player Notifier", "will notify if a player leaves/joined",
function()-- player joined/left lobby
loadstring(game:HttpGet("https://pastebin.com/raw/c5JacC0M"))()
  -- notifikation joiend/left
game.StarterGui:SetCore("SendNotification", {
  Title = "Player Notifier✅On";
  Text = "u will be notified wen players leave/join";

})
end)

MoreSection:NewButton("Kopy Avatars (IY)", "use infinite yield 'copyid (playername)'",
function()-- kopy avatar skript loadstring
loadstring(game:HttpGet("https://pastebin.com/raw/9Tmvpzn4"))()
end)


--buttons.MoreSektion
MoreSection:NewButton("Auto Grammar V2", "type with good punkuation(not that good so what)",
function()shared.CustomCorrections = {
  ["examplething12"] = "hello" -- if you say "examplething12" it will become hello
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/eosuwu/boblox/main/autogremer.lua"))()
end)

MoreSection:NewButton("Auto Klixker", "mighty klixker",
function()-- mighty klixker
getgenv().key = "Hostile"
loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/The-telligence/main/MC%20KSystem%202"))()
end)

MoreSection:NewButton("Anti Sit", "jumps if u sit",
function()loadstring(game:HttpGet("https://pastebin.com/raw/HDUKxdUt"))()
end)

MoreSection:NewButton("Faster Run", "run faster",
function()shared["本地播放器"] = game:FindService'Players'['LocalPlayer'] 
shared["数学"] = math
shared["开方"] = shared["数学"]['sqrt']
shared["本地播放器"]['Character']:FindFirstChildOfClass'Humanoid'.WalkSpeed = shared["开方"](1000) -- Speed exploit
end)

MoreSection:NewButton("Stand Alone", "kreates a platform to stand by yourself",
function()loadstring(game:HttpGet("https://pastebin.com/raw/eg8uzYiQ"))()
end)

MoreSection:NewButton("Kneel", "kneel and walk",
function()--Krouxh Animation ID: 287325678

local Crouch = Instance.new("Animation")
Crouch.AnimationId = "rbxassetid://287325678"
local DoIt = game:GetService("Players").LocalPlayer.Character.Humanoid:LoadAnimation(Crouch)
DoIt:Play()
end)

MoreSection:NewButton("Kneel V2 (c to toggle)", "C to toggle USE GENERATE ANY KEYBIND skript",
function()KEY = "C" -- Key to crouch
CROUCHWALKSPEED = 12 -- Walkspeed when you are crouching

local Player = game:GetService("Players").LocalPlayer;
local UserInputService = game:GetService("UserInputService");

local Character = Player.Character;
local Humanoid = Character:FindFirstChildOfClass("Humanoid");
local oldWS = Humanoid.WalkSpeed

local CrouchAnimation = Instance.new("Animation");
CrouchAnimation.AnimationId = "rbxassetid://287325678";
local Crouch = Humanoid:LoadAnimation(CrouchAnimation);
Crouch.Priority = Enum.AnimationPriority.Action

local Crouching = false
UserInputService.InputBegan:Connect(function(input,gameprocessed)
 if gameprocessed then return end
 if input.KeyCode == Enum.KeyCode[KEY] then
     Crouching = true
     Crouch:Play(.1)
     Humanoid.WalkSpeed = CROUCHWALKSPEED
 end
end)

UserInputService.InputEnded:Connect(function(input,gameprocessed)
 if gameprocessed then return end
 if input.KeyCode == Enum.KeyCode[KEY] then
     Crouching = false
     Crouch:Stop(.1)
     Humanoid.WalkSpeed = oldWS
 end
end)

Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
 if Crouching then
     Humanoid.WalkSpeed = CROUCHWALKSPEED
 end
end)
end)

--[ E M O J I S ]--
MoreSection:NewLabel("Emojis")
-- emoji buttons
MoreSection:NewButton("😁", "smiley", function()--player will say this
game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😁","All")
end)
MoreSection:NewButton("😆", "smiley", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😆","All")
end)
MoreSection:NewButton("😊", "smiley", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😊","All")
end)
MoreSection:NewButton("🍭", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍭","All")
end)
MoreSection:NewButton("🍭🍭", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍭🍭","All")
end)
MoreSection:NewButton("🍭🍭🍭", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍭🍭🍭","All")
end)
MoreSection:NewButton("🍭😋", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍭😋","All")
end)
MoreSection:NewButton("😍", "heart eyes", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😍","All")
end)
MoreSection:NewButton("💕", "2 hearts", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("💕","All")
end)
MoreSection:NewButton("❤️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("❤️","All")
end)
MoreSection:NewButton("❤️❤️❤️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("❤️❤️❤️","All")
end)
MoreSection:NewButton("🤣", "rofl", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤣","All")
end)
MoreSection:NewButton("🤣🤣", "rofl 2x", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤣🤣","All")
end)
MoreSection:NewButton("😘", "kiss emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😘","All")
end)
MoreSection:NewButton("😂", "laugh", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😂","All")
end)
MoreSection:NewButton("😂😂", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😂😂","All")
end)
MoreSection:NewButton("🥰", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🥰","All")
end)
MoreSection:NewButton("🥰🥰", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🥰🥰","All")
end)
MoreSection:NewButton("😊", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😊","All")
end)
MoreSection:NewButton("😋", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😋","All")
end)
MoreSection:NewButton("😋😋", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😋😋","All")
end)
MoreSection:NewButton("☺️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("☺️","All")
end)
MoreSection:NewButton("🤪", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤪","All")
end)
MoreSection:NewButton("😛", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😛","All")
end)
MoreSection:NewButton("😎", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😎","All")
end)
MoreSection:NewButton("😇", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😇","All")
end)
MoreSection:NewButton("😇🥰", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😇🥰","All")
end)
MoreSection:NewButton("👑", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("👑","All")
end)
MoreSection:NewButton("🐈", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🐈","All")
end)
MoreSection:NewButton("😮‍💨", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😮‍💨","All")
end)
MoreSection:NewButton("🙄", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🙄","All")
end)
MoreSection:NewButton("👀", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("👀","All")
end)
MoreSection:NewButton("😭", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😭","All")
end)
MoreSection:NewButton("🤔", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤔","All")
end)
MoreSection:NewButton("📷", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("📷","All")
end)
MoreSection:NewButton("📸", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("📸","All")
end)
MoreSection:NewButton("🥺", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🥺","All")
end)
MoreSection:NewButton("🤦‍♀️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤦‍♀️","All")
end)
MoreSection:NewButton("💔", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("💔","All")
end)
MoreSection:NewButton("💘", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("💘","All")
end)
MoreSection:NewButton("🍉", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍉","All")
end)
MoreSection:NewButton("😈", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😈","All")
end)
MoreSection:NewButton("🖤", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🖤","All")
end)
MoreSection:NewButton("😱", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😱","All")
end)
MoreSection:NewButton("😡", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😡","All")
end)
MoreSection:NewButton("😠", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😠","All")
end)
MoreSection:NewButton("😤", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😤","All")
end)
MoreSection:NewButton("🧚‍♀️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🧚‍♀️","All")
end)
MoreSection:NewButton("🤰", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤰","All")
end)
MoreSection:NewButton("👩‍💻", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("👩‍💻","All")
end)
MoreSection:NewButton("🙏", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🙏","All")
end)
MoreSection:NewButton("💤", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("💤","All")
end)
MoreSection:NewButton("🐣", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🐣","All")
end)
MoreSection:NewButton("🐤", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🐤","All")
end)
MoreSection:NewButton("🐥", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🐥","All")
end)
MoreSection:NewButton("🦋", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🦋","All")
end)
MoreSection:NewButton("😤", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😤","All")
end)
MoreSection:NewButton("☠️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("☠️","All")
end)
MoreSection:NewButton("🌹", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🌹","All")
end)
MoreSection:NewButton("🌺", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🌺","All")
end)
MoreSection:NewButton("🦆", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🦆","All")
end)
MoreSection:NewButton("🍿", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍿","All")
end)
MoreSection:NewButton("🍍", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍍","All")
end)
MoreSection:NewButton("🍔", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍔","All")
end)
MoreSection:NewButton("🥞", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🥞","All")
end)
MoreSection:NewButton("🍜", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍜","All")
end)
MoreSection:NewButton("🍝", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🍝","All")
end)
MoreSection:NewButton("☕️", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("☕️","All")
end)
MoreSection:NewButton("🎶", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🎶","All")
end)
MoreSection:NewButton("🎵", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🎵","All")
end)
MoreSection:NewButton("🫧", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🫧","All")
end)
MoreSection:NewButton("🇧🇫", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇧🇫","All")
end)
MoreSection:NewButton("🇯🇵", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇯🇵","All")
end)
MoreSection:NewButton("🇫🇷", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇫🇷","All")
end)
MoreSection:NewButton("🇰🇷", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇰🇷","All")
end)
MoreSection:NewButton("🇵🇹", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇵🇹","All")
end)
MoreSection:NewButton("🇵🇹", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇵🇹","All")
end)
MoreSection:NewButton("🇫🇷", "emoji", function()game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🇫🇷","All")
end)




--toggle the ui yes
local MoreSection = More:NewSection("no")

MoreSection:NewKeybind("Toggle ui", "toggle the ui yes", Enum.KeyCode.Insert, function()
    Library:ToggleUI()
end)




--Open/Klose GUI frame--
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local Frame2 = Instance.new("Frame")
local TextButton2 = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0,255,0)
Frame.Position = UDim2.new(0.858712733, 0, 0.1050062257, 0)
Frame.Size = UDim2.new(0, 90, 0, 30)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(148,0,211)
TextButton.Size = UDim2.new(0, 90, 0, 30)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "OPEN"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 22.000
TextButton.MouseButton1Click:connect(function()
Frame.Visible = false
Frame2.Visible = true    
local vim = game:service("VirtualInputManager")
vim:SendKeyEvent(true, "Insert", false, game)
end)

Frame2.Parent = ScreenGui
Frame2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Frame2.Position = UDim2.new(0.858712733, 0, 0.1050062257, 0)
Frame2.Size = UDim2.new(0, 90, 0, 30)
Frame2.Active = true
Frame2.Draggable = true

TextButton2.Parent = Frame2
TextButton2.BackgroundColor3 = Color3.fromRGB(128, 0, 32)
TextButton2.Size = UDim2.new(0, 90, 0, 30)
TextButton2.Font = Enum.Font.GothamBold
TextButton2.Text = "KLOSE"
TextButton2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton2.TextSize = 22.000
TextButton2.MouseButton1Click:connect(function()
    Frame2.Visible = false
    Frame.Visible = true
local vim = game:service("VirtualInputManager")
vim:SendKeyEvent(true, "Insert", false, game)
end)





Frame.Parent.Active = true
Frame.Parent.Draggable = true


---end----