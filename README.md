# Rejoin-roblox
# Rejoin the current server ur in

local TeleportService = game:GetService("TeleportService")
local Players = game:GetService("Players")

local player = Players.LocalPlayer
local placeId = game.PlaceId

-- Rejoin function
local function rejoinGame()
    TeleportService:Teleport(placeId, player)
end

-- Calling the rejoin function
rejoinGame()

