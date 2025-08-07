# TASK 3 - Terraform Docker Provisioning

## Objective
Provision an Nginx Docker container using Terraform.

## Steps Followed

1. Installed Docker and Terraform on local system.
2. Created a `main.tf` file to define Docker provider and Nginx container.
3. Used the Docker provider to:
   - Pull the latest Nginx image.
   - Run the container with port `8080:80`.
4. Ran the Terraform lifecycle:
   - `terraform init`
   - `terraform plan`
   - `terraform apply`
   - Verified the running container using `docker ps`.
   - Accessed the website via `http://localhost:8080`.
5. Destroyed the infrastructure using `terraform destroy`.

## Commands Used
```bash
terraform init
terraform plan
terraform apply
docker ps
terraform destroy
```
#### Output website

<img width="1920" height="663" alt="Welcome to nginx! - Brave 07-08-2025 13_43_48" src="https://github.com/user-attachments/assets/8c8f2525-f970-4525-b0d8-53b790c9d6b8" />
