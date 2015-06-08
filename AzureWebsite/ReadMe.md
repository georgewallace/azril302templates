# Very simple deployment of a Empty Website to Azure 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgeorgewallace%2Fazril302templates%2Fmaster%2FAzureWebsite%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Built by: [georgewallace](https://github.com/georgewallace)

This template allows you to deploy a simple Website to Azure with App Inishgts configured as well. 

Below are the parameters that the template expects: 

| Name   | Description    |
|:--- |:---|
| Test App Service PlanName  | Name for the App Service Plan to be used. |
| Test App Service PlanLocation  | Location to deploy the website to. Allowed values: ["East US", "West US", "West Europe", "East Asia", "South East Asia"]  |
| Test App Service PlanSKU  | The type of Service Plan. Allowed values: ["Free", "Shared", "Basic", "Standard"  |
| Test App Service PlanWorkerSize  | Number of scaled sites. Allowed values: ["0","1","2"] |
| Test Web AppName  | The Name of the Website |
| sizeOfDiskInGB | The size of disk in GB | 
