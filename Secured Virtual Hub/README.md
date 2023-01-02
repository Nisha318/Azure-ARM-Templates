$RGName = "fw-manager-rg"
   
New-AzResourceGroupDeployment -ResourceGroupName $RGName -TemplateFile FirewallManager.json -TemplateParameterFile FirewallManager.parameters.json



![18 - Deploy the servers](https://user-images.githubusercontent.com/12909665/210278328-dc2a6484-51c3-436c-9a0f-b94b3bb851dd.jpg)
