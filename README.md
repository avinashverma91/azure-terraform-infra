# Azure Terraform Infrastructure

This project provisions an **Azure infrastructure** using Terraform, automating the creation of cloud resources. The setup includes a **Virtual Network (VNet), Subnet, Virtual Machine (VM), Storage Account, and Key Vault**.

## 📌 Features
- **Resource Group**: Organizes all resources in Azure.
- **Virtual Network (VNet) & Subnet**: Provides networking for the infrastructure.
- **Virtual Machine (VM)**: Deploys an Ubuntu 18.04 VM with SSH access.
- **Storage Account**: Stores data with Standard_LRS replication.
- **Azure Key Vault**: Securely manages secrets and keys.

## 🛠 Prerequisites
- Terraform installed ([Download Terraform](https://developer.hashicorp.com/terraform/downloads))
- Azure CLI installed ([Install Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli))
- An Azure account ([Create free account](https://azure.microsoft.com/en-us/free/))

## 🚀 Deployment Steps
1. **Clone the repository**:
   ```sh
   git clone https://github.com/avinashverma91/azure-terraform-infra.git
   cd azure-terraform-infra
   ```
2. **Initialize Terraform**:
   ```sh
   terraform init
   ```
3. **Plan the deployment**:
   ```sh
   terraform plan
   ```
4. **Apply the configuration**:
   ```sh
   terraform apply -auto-approve
   ```

## 🔍 Future Enhancements
- Add **CI/CD automation** for Terraform deployment.
- Implement **Azure Kubernetes Service (AKS)**.
- Enable **Monitoring and Logging** with Azure Monitor.

## 📜 License
This project is open-source and available under the MIT License.
