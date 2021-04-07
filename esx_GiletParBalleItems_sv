ESX = nil

TriggerEvent('esx:getSharedObject', function(obj) ESX = obj end)


ESX.RegisterUsableItem('bulletproof', function(source)

	local xPlayer = ESX.GetPlayerFromId(source)

	TriggerClientEvent('esx_useitem:bulletproof', source)
	xPlayer.removeInventoryItem('bulletproof', 1)

end)
