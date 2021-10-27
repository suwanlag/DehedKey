local key = _G.Key
local check = "https://whitelistseenhubv2.000webhostapp.com/Check.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/suwanlag/DEHED-HUB/main/DEHED.md"))()
else
game.Players.LocalPlayer:Kick("คีย์ผิดว่ะข่าบ")
end
