# ☁ Cloud_Red team_Homelab
Deploy an attack/defend homelab.

# Topology 
Provider: AWS.

![Topology](https://github.com/HelixY2J/cloud_red-team_homelab/blob/main/img/topology_homelab.png)




# Deploy 

Option 1 :

Download Terraform: https://developer.hashicorp.com/terraform/downloads 

`terraform init`: Initialize Terraform.

`terraform plan`: Plan Terraform configuration.

`terraform apply -var="aws-key"`: Specify the public key name created in AWS in EC2 -> Network & Security.
- Add Public Key Name in between double quotes.

`terraform destory`: Destroy AWS infrastructure.

Option 2 :

Provision with AWS console CLI