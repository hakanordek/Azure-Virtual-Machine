###### Main Terraform code created to run on Version 13.5, latest version as of 11/2020
###### Functions with AzureRM Version 2.37.0, latest version as of 11/2020
###### Dated 11/23/2020
###### Creates Vnet, Subnet and Linux Virtual Machine using backend remote state
###### Port 22 is allowed and NSG attached to VM. 
###### Hard-coding is avoided, Modules are used