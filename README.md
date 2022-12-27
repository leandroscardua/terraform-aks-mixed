# Create a AKS cluster with Azure AD Group Authentication using kubelogin
#
#Install Kubelogin
https://github.com/Azure/kubelogin#setup-windows
#
#Linux
#
```
export TF_VAR_wn_user_name=
export TF_VAR_wn_user_password=''
```

#Windows
#
#Install Kubelogin
https://github.com/Azure/kubelogin#setup
#
```
set TF_VAR_wn_user_name=
set TF_VAR_wn_user_password=''
```
#Terraform
# add the variables below, before run it.

terraform init

terraform fmt

terraform validate

terraform plan

terraform apply -auto-approve

