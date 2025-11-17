# tfdemo
1. Download Terraform and add it to your PATH
2. Create a GitHub project (repo)
3. Clone the repo locally
```
git clone <PROJECT_URL>
cd <PROJECT>
```
4. Add your Terraform files
5. Open a terminal and navigate to the project folder
6. Log in to Azure
```
az login
```
7. Run Terraform commands
```
terraform init
terraform plan
terraform apply
```
8. To destroy resources without confirmation
```
terraform destroy -auto-approve
```