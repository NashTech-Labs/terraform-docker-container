### Prerequisites

1. An IDE of your choice.

2. An AWS Account.

3. Terraform already installed and configured.

### Create Accompanying Files :

* providers.tf
* variables.tf
* vpc.tf
* subnets.tf
* main.tf
* terraform.tfvars
* .gitignore


Once all of our files have been create , please run the following commands from the terminal.
, In order to deploy Docker Container in AWS Cluster using Terraform .



We have four main Terraform commands to use , they are as :

* terraform init
* terraform plan
* terraform apply
* terraforn destroy 



Let's see why these files are used:

**terraform init**

In order to initialise our working directory containing our terraform code.

**terraform plan**

It is used to preview our infrastructure prior to executing our terraform code.

**terraform apply**

It is used to apply all the changes specified in the plan into motion.

 
let's apply them all:


```
terraform init
```

```
terraform plan
```

```
terraform apply
```


Once you’ve confirmed that the resources were successfully created, in order to avoid unnecessary charges, ensure that all resources are destroyed.


This can be achieved by entering the Terraform destroy command in your terminal as :



**terraform deploy**
It is used in order to delete all the resources together.



```
terraform destroy
```





**NOTE**

.gitignore is a file text that tells Git which files or directories to ignore when committing your project to Github. Our terraform.tfvars file will be the file ignore for it contains our secret and access keys.