# Create a AKS cluster with Azure AD Group Authentication using kubelogin
#
#az login with terraform
https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/azure_cli
#Install Kubelogin
https://github.com/Azure/kubelogin#setup
#
#Linux
#
```
export TF_VAR_wn_user_name=
export TF_VAR_wn_user_password=''
```

#Windows
#
#az login with terraform
https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/azure_cli
#Install Kubelogin
https://github.com/Azure/kubelogin#setup-windows
#
```
set TF_VAR_wn_user_name=
set TF_VAR_wn_user_password=''
```
#Terraform
# add the variables below, before run it.

terraform init

terraform validate

terraform plan

terraform apply -auto-approve

