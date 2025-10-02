# Azure DevOps

# 📌 **Core Azure Services to Study (DevOps + Cloud Engineer Focus)**

### 1️⃣ **Compute**

* **Azure Virtual Machines (VMs)** → like AWS EC2
* **App Service** → like Elastic Beanstalk
* **Azure Functions** → like AWS Lambda
* **Azure Kubernetes Service (AKS)** → like EKS
* **Azure Container Instances (ACI)** → like Fargate

---

### 2️⃣ **Networking**

* **Virtual Network (VNet)** → like VPC
* **Subnet, NSG (Network Security Groups)** → like Security Groups/NACL
* **VPN Gateway & ExpressRoute** → like VPN & Direct Connect
* **Azure Front Door / Traffic Manager** → like Route 53 + Global Accelerator
* **Azure Load Balancer & Application Gateway (WAF)** → like ALB/NLB
* **Private Link & Service Endpoints** → like VPC Endpoints

---

### 3️⃣ **Storage**

* **Azure Blob Storage** → like S3
* **Azure Files (SMB/NFS)** → like EFS
* **Disk Storage** → like EBS
* **Archive Storage** → like Glacier

---

### 4️⃣ **Identity & Security**

* **Azure Active Directory (AAD)** → like IAM + Cognito + SSO
* **Role-Based Access Control (RBAC)** → IAM roles & policies
* **Managed Identity** → like IAM Roles for EC2
* **Azure Key Vault** → like AWS KMS + Secrets Manager
* **Azure Security Center (Defender for Cloud)** → like AWS Security Hub

---

### 5️⃣ **Databases**

* **Azure SQL Database** → like RDS (SQL Server)
* **Cosmos DB** → like DynamoDB
* **Azure Database for MySQL/PostgreSQL** → like RDS MySQL/Postgres

---

### 6️⃣ **Monitoring & Logging**

* **Azure Monitor** → like CloudWatch
* **Log Analytics Workspace** → advanced logs/queries
* **Application Insights** → like X-Ray + CloudWatch Logs
* **Azure Service Health** → like AWS Personal Health Dashboard

---

### 7️⃣ **DevOps & CI/CD**

* **Azure DevOps Services** (Repos, Pipelines, Boards, Test Plans, Artifacts)
* **GitHub Actions + Azure Integration**
* **ARM Templates & Bicep** (native IaC)
* **Terraform on Azure**

---

### 8️⃣ **Containers & Serverless**

* **Azure Kubernetes Service (AKS)** (deep dive)
* **Azure Container Registry (ACR)** → like ECR
* **Azure Functions** → like Lambda
* **Event Grid** → like EventBridge
* **Service Bus** → like SQS + SNS

---

### 9️⃣ **Security & Governance**

* **Azure Policy** → like AWS Organizations SCPs
* **Blueprints** → governance templates
* **Azure Cost Management + Budgets** → like AWS Cost Explorer

---

### 🔟 **Extras (Good to Know)**

* **Azure DevTest Labs** → sandbox for testing
* **Azure Site Recovery** → disaster recovery
* **Azure Backup** → snapshot/backup management

---

# 🎯 Prioritization for You (DevOps background)

1. **Core Infra** → VNet, VM, Storage, RBAC, AAD
2. **AKS + ACR + Pipelines** → containers + CI/CD
3. **Monitoring** → Azure Monitor + App Insights + Logs
4. **IaC** → ARM/Bicep/Terraform
5. **Security + Governance** → Key Vault, Policy, Defender

---

Here’s a **AWS → Azure Service Mapping Table (DevOps + Cloud Engineer Focus)**:

---

# 📊 **AWS vs Azure Services Mapping**

| **Category**                | **AWS Service**                 | **Azure Equivalent**                            |
| --------------------------- | ------------------------------- | ----------------------------------------------- |
| **Compute**                 | EC2                             | Virtual Machines (VM)                           |
|                             | Elastic Beanstalk               | App Service                                     |
|                             | Lambda                          | Azure Functions                                 |
|                             | ECS (Fargate)                   | Azure Container Instances (ACI)                 |
|                             | EKS                             | Azure Kubernetes Service (AKS)                  |
|                             | AMI                             | Azure Managed Images                            |
| **Networking**              | VPC                             | Virtual Network (VNet)                          |
|                             | Subnet + Route Table            | Subnet + UDR (User Defined Routes)              |
|                             | Security Groups / NACLs         | NSG (Network Security Group)                    |
|                             | Elastic Load Balancer (ALB/NLB) | Azure Load Balancer / Application Gateway (WAF) |
|                             | Route 53                        | Azure DNS / Traffic Manager / Front Door        |
|                             | Direct Connect                  | ExpressRoute                                    |
|                             | VPN                             | VPN Gateway                                     |
|                             | VPC Endpoints                   | Service Endpoints / Private Link                |
| **Storage**                 | S3                              | Blob Storage                                    |
|                             | EBS                             | Managed Disks                                   |
|                             | EFS                             | Azure Files                                     |
|                             | Glacier                         | Azure Archive Storage                           |
| **Identity & Security**     | IAM                             | Azure Active Directory (AAD) + RBAC             |
|                             | IAM Roles for EC2               | Managed Identity                                |
|                             | KMS                             | Key Vault                                       |
|                             | Secrets Manager                 | Key Vault (Secrets)                             |
|                             | Organizations + SCP             | Azure Policy / Blueprints                       |
|                             | Security Hub / GuardDuty        | Microsoft Defender for Cloud                    |
| **Databases**               | RDS (SQL Server)                | Azure SQL Database                              |
|                             | DynamoDB                        | Cosmos DB                                       |
|                             | RDS MySQL/Postgres              | Azure Database for MySQL/PostgreSQL             |
|                             | Aurora                          | Hyperscale (Azure SQL)                          |
| **Monitoring & Logging**    | CloudWatch Metrics              | Azure Monitor                                   |
|                             | CloudWatch Logs                 | Log Analytics Workspace                         |
|                             | X-Ray                           | Application Insights                            |
|                             | Personal Health Dashboard       | Azure Service Health                            |
| **DevOps Tools**            | CodeCommit                      | Azure Repos                                     |
|                             | CodeBuild                       | Azure Pipelines (Build)                         |
|                             | CodeDeploy                      | Azure Pipelines (Release)                       |
|                             | CodePipeline                    | Azure DevOps Pipelines                          |
|                             | CloudFormation                  | ARM Templates / Bicep                           |
|                             | Terraform (same tool)           | Terraform on Azure                              |
|                             | ECR                             | Azure Container Registry (ACR)                  |
| **Messaging & Integration** | SQS                             | Azure Service Bus Queue                         |
|                             | SNS                             | Azure Service Bus Topics / Event Grid           |
|                             | EventBridge                     | Event Grid                                      |
|                             | Kinesis                         | Event Hub                                       |
| **Governance & Cost**       | Cost Explorer                   | Cost Management + Budgets                       |
|                             | Trusted Advisor                 | Advisor                                         |
|                             | Control Tower                   | Blueprints                                      |

---

