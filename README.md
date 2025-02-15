# About

This is a repo of an AWS configuration of the infrastructure in the diagram using Terraform.

![](images/diagramwk4.png)


# Prerequisites

1. Terraform version `1.10.5` or greater
2. AWSCLI version `2.23.5` or greater
> *configure your AWSCLI credentials by creating a user in AMI roles*
# Usage

3. Clone repository
```bash
git clone https://github.com/jyleoxcino/lab-week4-terraform.git
```

4. Generate SSH Key
```bash
ssh-keygen -t ed25519 -f ~/.ssh/<key-name> -C "<commnet-to-identify-key>"
```

5. Add generated public key to cloud-config.yml

6. Initialize Terraform working directory
> initialize directory and install providers
```bash
terraform init
```

7. Validate Terraform configuration
> Verify the configuration is working and you have the required pre-requisites
```bash
terraform validate 
```

8. Check Terraform Plan
> Review Terraform configuration and AWS infrastructure
```bash
terraform plan
```

9. Apply and build infrastructure
```bash
terraform apply
```
