# Case study

this repo contains practical cloud work 

# Azure resourse provisioning with terraform
in this project we provisioned azure resourses through terraform, managing and monitoring kubernetes clusters.

the repository contains 2 folders, terraform and k8s-manifest, where the terraform codes contains all the terraform 
related codes for managing and maintaining the state of the infrastructure

# Terraform commands
- `terraform init` : this initializes the provider in which was specified in the providers.tf file
- terraform validate: performs check in syntax available in the code
- terraform plan: performs a dry run of the desired state
- terraform apply: this command is used to achieve the desired state from the actual state
- terraform fmt: is used to perform a format to user friendly and readable formaat
- terraform destroy: is used to destroy created resource and perform cleanup

# Aks
aks resource was created to manage 2 nodes for availability 
