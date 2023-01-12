# STAR-HUB-V1local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("STAR HUB V1.0.0", "DarkTheme")

-- MAIN --
local Main = Window:NewTab("Dahood Scripts")
local MainSection = Main:NewSection("Dahood Scripts")


MainSection:NewButton("SwagMode", "Best DH Script", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))()
end)

MainSection:NewButton("Faded", "Artic Dahood GUI", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded-Grid/main/YesEpic", true))()
end)

local Main = Window:NewTab("DHC Scripts")
local MainSection = Main:NewSection("DHC")

MainSection:NewButton("Crostide GUI", "Good selling GUI ( join group to use )", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Crostide/cdhc/main/gui'))()

end)

MainSection:NewButton("Spooky GUI", "DHC Selling GUI ", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/halloweevn/Spooky/main/gui.lua', true))()

end)

local Tab = Window:NewTab("Prison Life")

local Section = Tab:NewSection("2023 Prison Life Scripts")

Section:NewButton("Prison Ware", "Cool script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))()
end)

local Tab = Window:NewTab("Blox Fruits")

local Section = Tab:NewSection("Blux Fruits 2023")

Section:NewButton("Blox Fruits GUI", "Most OP Blox Fruit GUI", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

Section:NewButton("Blox Fruit AutoFarm", "Auto farm for blox fruit", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/sinret/rbxscript.com-scripts-reuploads-/main/bf2", true))()

end)

local Tab = Window:NewTab("Natural Disaster")

local Section = Tab:NewSection("OP Natural Disaster Script")

Section:NewButton("NDS GUI", "godly script for NDS", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringUjHI6RQpz2o8", true))()
end)


local Tab = Window:NewTab("Murder Mystery 2")

local Section = Tab:NewSection("MM2 Scripts")

Section:NewButton("MM2 Menu", "Best mm2 script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()

end)

local Tab = Window:NewTab("Bee Swarm Sim")

local Section = Tab:NewSection("Bee Swarm Menu's")

Section:NewButton("Bee Swarm Menu", "OP MENU", function()
    loadstring(game:HttpGet('https://s.kometa.ga/kometa.lua'))()
end)

local Tab = Window:NewTab("Brookhaven")

local Section = Tab:NewSection("Brookhaven Troll Script")

Section:NewButton("Brookhaven Troll", "OP GUI", function()
    loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/93d59eb6d826262396d8436868e73033/raw/eaa85b6545ff8a06fe89d7093cb3666461b628e8/gaga", true))()
end)

local Tab = Window:NewTab("Egoist")

local Section = Tab:NewSection("Egoist Script")

Section:NewButton("Egoist GUI", "become the best with a click of a button", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Mstir16/legocheats/main/archive/EGOIST/script.lua"))()
end)

local Tab = Window:NewTab("Greenville")


local Section = Tab:NewSection("Greenville Autofarm")

Section:NewButton("GV Script AF", "yah u become rich thats all", function()
    loadstring(game:HttpGet("https://carhub.wtf/script"))()
end)

Section:NewDropdown("Script Credits", "DropdownInf", {"built by tqze#2203",}, function(currentOption)
    print(currentOption)
end)


local Tab = Window:NewTab("Credits")

local Section = Tab:NewSection("made by tqze#2203 ( dm for help / ideas )")
