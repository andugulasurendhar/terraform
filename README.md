Terraform
<br><b>Main commands</b>:
 <br> init:          Prepare your working directory for other commands
 <br> validate:      Check whether the configuration is valid
 <br> plan:          Show changes required by the current configuration
<br>  apply:         Create or update infrastructure
 <br> destroy:       Destroy previously-created infrastructure
 
 <br>**If we loose the state file then we can still import the state of the resources by import command.**<br>
eg: terraform import azurerm_subnet.exampleSubnet /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/mygroup1/providers/Microsoft.Network/virtualNetworks/myvnet1/subnets/mysubnet1
<br> ->we need to import for all the resources. we get all the details in the cloud we are using.

**To Destroy Specific module we use the below command **<br> $ terraform destroy --target=module.module_prod // where module_prod is the module name

