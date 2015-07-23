# Very simple deployment of an Empty Website to Azure 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgeorgewallace%2Fazril302templates%2Fmaster%2FDCwithVMS%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

Built by: [georgewallace](https://github.com/georgewallace)

This template allows you to deploy a simple Website to Azure with App Insights configured as well. 

Below are the parameters that the template expects: 

| Name   | Description    |
|:--- |:---|
| Service Plan Name  | Name for the App Service Plan to be used. |
| Service Plan Location  | Location to deploy the website to. Allowed values: ["East US", "West US", "West Europe", "East Asia", "South East Asia"]  |
| Service Plan SKU  | The type of Service Plan. Allowed values: ["Free", "Shared", "Basic", "Standard"]  |
| Service Plan Worker Size  | Number of scaled sites. Allowed values: ["0","1","2"] |
| Web App Name  | The Name of the Website |

