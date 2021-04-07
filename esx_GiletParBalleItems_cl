ESX = nil
local CurrentActionData   = {}
local lastTime            = 0

Citizen.CreateThread(function()
	while ESX == nil do
		TriggerEvent('esx:getSharedObject', function(obj) ESX = obj end)
		Citizen.Wait(0)
	end
end)


RegisterNetEvent('esx_useitem:bulletproof3')
AddEventHandler('esx_useitem:bulletproof3', function()
  
    local playerPed = GetPlayerPed(-1)
    
			SetPedComponentVariation(playerPed, 9, 9, 3, 2)
			AddArmourToPed(playerPed, 100)
      SetPedArmour(playerPed, 100)
    
end)
