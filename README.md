# Terraform Docker Infrastructure

## Objective

To provision a Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Nginx

## Terraform Commands Used

1. terraform init
2. terraform validate
3. terraform plan
4. terraform apply
5. terraform state list
6. terraform show
7. terraform destroy

## Infrastructure Created

Terraform was used to create an Nginx Docker image and an Nginx Docker container.

The container port 80 was mapped to host port 8080.

The application was tested using:

http://localhost:8080

## Result

The Docker container was successfully created using Terraform and later destroyed using terraform destroy.
