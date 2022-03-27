
# Deploying Mediawiki app into Azure Kubernetes service cluster

This Project Deploy Mediawiki Application to AKS Cluster using Jenkins CI/CD. This Project is divided into Four following parts -

# 1)Terraform
It contains terraform(.tf) files which automate our infrastructure creation.

# 2)Docker
It contains mediawiki and database Dockerfile,which will be use to containerize our Application.

# 3)Jenkins
It contains Jenkins file,Which automate our continuous integration and continuous deployment process.

# 4)Kubernetes
It Contains Manifest files,Which will be used to creating our object like Deployment,Services,Persistent-volume etc and manage the containers.

# Prerequisites
1. Install Terraform and git on the machine.
2. Account setup in Azure.
3. Kubectl is installed on your machine.
4. Azure cli is installed.
5. Install ruby and ruby json.


# Steps
# A. Steps for creating AKS Cluster using Terraform.
1. az login(Choose your Microsoft credentials.)
2. terraform init
3. terraform plan
4. terraform apply -auto-approve
