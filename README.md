# terraform-aws-eks
I provision EKS using Terraform with managed node groups, IAM roles, and VPC networking. I use Terraform for repeatability and AWS-managed node groups for operational simplicity.

# Terraform AWS EKS Cluster

This project provisions an AWS EKS cluster using Terraform.

## Components
- VPC and public subnets
- EKS control plane
- Managed node group
- IAM roles and policies

## How to Deploy
terraform init
terraform apply

## Configure kubectl
aws eks --region ap-south-1 update-kubeconfig --name devops-eks-cluster

## Use Case
Production-ready Kubernetes cluster for containerized workloads.

## Author
Ashutosh Upadhyay
Senior DevOps Engineer

