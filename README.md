# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####

once you are done with other steps follow the following to merge to main branch the step apply terraform and create the resources 
in the Terminal 
1041  cd iac-vprofile2/
 1042  git branch -a
 1043  git checkout stage
 1044  ls
 1045  git status
 1046  cd ..
 1047  cd main-iac/
 1048  ls
 1049  git pull
 1050  git status
 1051  git merge stage
 1052  git checkout stage
 1053  git checkout main
 1054  git status
 1055  git merge stage
 1056  git push origin main  -->
 
#####
