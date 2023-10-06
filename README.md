local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local window = kavoUi.CreateLib("Obby But You're on a Bike","BloodTheme")
 
---Tabs
 
local Tab1 = window:NewTab("Mundo 1")
local Tab1Section = Tab1:NewSection("Mundo 1")
local Tab2 = window:NewTab("Sup")
local Tab2Section = Tab2:NewSection("Sup is word")
local Tab3 = window:NewTab("Credits")
local Tab3Section = Tab3:NewSection("Made By biel17125")
local Tab3Section = Tab3:NewSection("biel17125")
 
---Buttons
 
Tab1Section:NewButton("Complete World 1 (Be on the map 1)","Complete world 1",function()
 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104, -3, -20965)
end)

Tab1Section:NewButton("Complete World 2 (Be on the map 2)","Complete world 2",function()
 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(105, -3, -13629)
end)
 
Tab1Section:NewButton("Complete World 3 (Be on the map 3)","Complete world 3",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(100, -4, -18340)
end)
 
Tab1Section:NewButton("Complete World 4 (Be on the map 4)","Complete world 4",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109, -4, -14999)
end)

Tab1Section:NewButton("Complete World 5","Complete world 5",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(105, -3, -22321)
end)

Tab2Section:NewButton("Keyboard","Pc Like Keyboard",function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
end)
