This script is only for Buyers or Players exploiters in discord this the Script which i will be supporting on kolher discord server.

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Chaos Support", "Synapse")

--Tab--
local Discord = Window:NewTab("Discord")
local AttackGames = Window:NewTab("AttackGames")


--Section--
local Section = Discord:NewSection("Others")
local Section = AttackGames:NewSection("AttackGames")
local Section = Executes:NewSection("Executes")
local Section = Serverside:NewSection("Serverside")


--Buttons/Link--
Section:NewButton("Discord", "Link Here https://discord.gg/y6BFQzHS ", function()
    
end)
Section:NewButton("infinite Yield", "Alot Commands", function()
    
end)

--RemoteSpy/SimpleSpy--
Serverside:NewButton("Serverside 1", "Serverside ", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/ChaosOwnerHubScript/Remote-Spy-lol/main/README.md"), true))()
end)
--OP Executes Coming soon--
Executes:NewButton("Synapse X Script", "Kolher uses synapse x.", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/ChaosOwnerHubScript/Synapse-X2/main/README.md"), true))()
end)
Executes:NewButton("Coming soon", "Offline lol", function()
    print("Coming soon.")
end)
Executes:NewButton("Coming soon", "ButtonInfo", function()
    print("Clicked")
end)
