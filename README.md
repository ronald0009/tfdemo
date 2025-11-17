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
9. Add your project files into the cloned folder
```
git add .
git commit -m "Add project files"
```
10. Push the files to GitHub
```
git push origin main
```
11. Continue working (future updates)
```
git add .
git commit -m "Update README"
git push
```
