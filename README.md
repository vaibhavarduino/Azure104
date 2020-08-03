# Azure104
azure practices
to run in cli after updateing custom jason file to cli
az vm extension set --resource-group azuredemo --vm-name linuxvm --name customScript --publisher Microsoft.Azure.Extensions --settings customscript.json
