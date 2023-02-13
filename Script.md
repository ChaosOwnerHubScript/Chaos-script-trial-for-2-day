This script is only for Buyers or Players exploiters in discord this the Script which i will be supporting on kolher discord server.

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Chaos Support", "Synapse")
 
--Tab--
local Discord = Window:NewTab("Discord")
local AttackGames = Window:NewTab("AttackGames")
 
 
--Section--
local Section = Discord:NewSection("Others")
local Section = AttackGames:NewSection("AttackGames")
 
 
--Buttons/Link--
Section:NewButton("Discord Kolher", "Join ", function()
    discord.gg/y6BFQzHS
end)
Section:NewButton("infinite Yield", "Alot Commands", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)
