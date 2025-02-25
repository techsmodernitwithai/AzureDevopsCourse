# Comprehensive DevOps Training Program
# Module 1: Azure Cloud Overview
- What is cloud computing?
- Benefits of cloud computing (Scalability, Cost Efficiency, Security, Agility)
- Types of cloud computing (Public, Private, Hybrid)
- Cloud service models (IaaS, PaaS, SaaS)

### Introduction to Microsoft Azure
- What is Microsoft Azure?
- Key advantages of Azure
- Understanding Azure Regions & Availability Zones
- Creating a free Azure account
- Understanding Azure Portal navigation
- Overview of Azure CLI & PowerShell

### Azure Compute Services
- Virtual Machines (VMs)
- Azure App Services
- Azure Functions (Serverless computing)
- Azure Kubernetes Service (AKS)

### Azure Storage Services
- Blob Storage
- Azure Files
- Table Storage
- Disk Storage

### Azure Networking Services
- Virtual Networks (VNet)
- Azure Load Balancer
- Azure Application Gateway
- ExpressRoute & VPN Gateway

### Azure Identity & Security Services
- Microsoft Entra ID
- Role-Based Access Control (RBAC)
- Azure Security Center
- Azure Key Vault

### Azure Management Tools
- Azure Portal
- Azure CLI & PowerShell
- Azure Resource Manager (ARM)

### Azure Monitoring & Performance
- Azure Monitor
- Azure Log Analytics
- Application Insights

### Governance & Cost Optimization
- Azure Policy
- Azure Cost Management & Billing
- Azure Advisor

## Hands-on Labs & Case Studies

### Hands-on Labs
- Deploy a Virtual Machine in Azure
- Set up a Web App using Azure App Services
- Configure Azure Storage (Blob & File Share)

## Module 2: Advanced Git Techniques
- Working with Remote Repositories  
- Pushing and Pulling Changes  
- Stashing Changes  
- Rebasing  
- Cherry-picking  
- Understanding Different Workflows (e.g., Git Flow, GitHub Flow)  
- Choosing the Right Workflow for Your Project  
- Best Practices  

## Module 3: Introduction to Azure DevOps
- Understanding Azure DevOps Organization  
- Azure DevOps Projects  
- Organization and Project Settings  
- Understanding Azure Boards and Work Items  

## Module 4: Working with Azure Repos
- Overview of Azure Repos  
- Key Features and Benefits  
- Setting Up Azure Repos  
- Connecting Git Repositories to Azure Repos  
- Pushing and Pulling Changes  
- Managing Branches in Azure Repos  
- Code Reviews  
- Pull Requests and Approvals  

## Module 5: Advanced Git Operations in Azure Repos
- Cloning Azure Repos  
- Forking Azure Repos  
- Cherry-picking  
- Stashing Changes  
- Hands-on Projects and Presentations  

## Module 6: Introduction to CI/CD in Azure DevOps
- Overview of Continuous Integration and Continuous Deployment (CI/CD)  
- Benefits of CI/CD in DevOps  
- Setting Up Azure DevOps for CI/CD  
- Understanding CI Pipelines  
- Creating a .NET Core Test Project  
- Configuring Build Pipelines  

## Module 7: Deploying Applications in Azure
- Creating a Web App in Azure  
- Understanding Entra ID and Creating App Registration  
- Creating a Service Connection  
- Creating a Web App in Azure  
- Deploying a Project in WebApp Using Classic Release Pipeline  

## Module 8: Multi-Stage Release Pipelines
- Creating a Multi-Stage Release Pipeline  
- Verify Changes in Code Trigger Pipeline Running Automatically  
- Enabling Continuous Deployment and Adding Approvals Before Releasing on Production Slot  

## Module 9: Introduction to Infrastructure as Code (IaC) with ARM Templates
- Understanding ARM Templates  
- Detailed Explanation of ARM Templates  
- Installing Visual Studio Code  
- Understanding ARM Template Components  

## Module 10: Writing and Deploying ARM Templates
- Writing the First ARM Template Code to Deploy a Resource Group  
- Writing an ARM Template to Deploy a Storage Account  
- Writing an ARM Template to Deploy a Web App  
- Deploying Code in Azure  

## Module 11: Advanced ARM Template Deployment
- Creating an ARM Template to Deploy a Web App  
- Pushing Code to Azure Repos  
- Understanding Continuous Delivery and Continuous Deployment  
- Understanding CD Pipelines  
- Configuring Release Pipelines to Deploy Infrastructure and Web Apps Together  
- Deploying Applications  

## Module 12: Advanced CI/CD Pipelines
- Implementing Multi-Stage Pipelines  
- Using Templates and Variables  
- Integrating with Third-Party Tools  
- Best Practices for CI/CD Pipelines  
- Troubleshooting and Debugging Pipelines  
- Real-world Examples and Case Studies  

## Module 13: Understanding Azure DevOps Agents
- What is an Agent Pool?  
- Microsoft Hosted Agent  
- Self-hosted Agent  
- Deploying an Agent Pool in a Local Machine or Azure Hosted VM  

## Module 14: Introduction to YAML for CI/CD
- Introduction to YAML  
- Understanding Key-Value Pairs in YAML  
- Understanding Dictionaries in YAML  
- Understanding Indentation in YAML  
- Understanding Nested Lists and Dictionaries  

## Module 15: Building CI/CD Pipelines with YAML
- Writing the First Build Pipeline Using YAML  
- Writing a Deployment Pipeline in YAML  

## Module 16: Advanced YAML Pipeline Features
- Understanding Lifecycle Hooks  
- Deployment Strategies in YAML  
- Writing a Multi-Stage Deployment Pipeline Using YAML  
- Using Predefined Variables  

## Module 17: Managing Azure Artifacts
- Introduction to Azure Artifacts  
- Managing and Using Packages in Azure Artifacts  

## Module 18: Securing Azure Pipelines
- Security in Azure Pipelines  
- Managing Access and Permissions  
- Best Practices for Secure CI/CD Pipelines  

## Module 19: Database Automation in DevOps
- Introduction to Database Automation  
- Automating Database Deployments with Azure Pipelines  

## Module 20: Secure Secrets Management with Azure Key Vault
- Integrating Key Vault with Database Automation Projects  
- Managing Secrets and Secure Connections in Azure  

## Module 21: Introduction to Terraform for Infrastructure Automation (Part 1)
- What is Terraform?  
- Understanding Terraform Basics  
- Setting Up Terraform for Azure  

## Module 22: Advanced Terraform Concepts (Part 2)
- Writing Terraform Scripts for Infrastructure Deployment  
- Using Terraform State and Modules  

## Module 23: Deploying Terraform Code via Azure Pipelines
- Creating a Terraform Pipeline in Azure DevOps  
- Automating Infrastructure Deployment with Terraform  

## Module 24: Deploying .NET Projects with Terraform
- Deploying a .NET Project in WebApp Using Terraform  
- Best Practices for Infrastructure as Code and DevOps 

# Module 25: Ansible Overview and Writing Playbooks & Roles

## Introduction to Ansible

### What is Ansible?
- Open-source automation tool
- Used for configuration management, application deployment, and task automation
- Agentless architecture using SSH and WinRM
- Written in Python, uses YAML for automation scripts

### Benefits of Ansible
- Simple, human-readable automation
- Agentless deployment
- Idempotent execution
- Scalable and flexible

### Ansible Architecture
- Control Node
- Managed Nodes
- Inventory
- Modules
- Playbooks
- Roles
- Plugins

## Writing Ansible Playbooks

### Understanding Playbooks
- Written in YAML format
- Define automation tasks
- Use `tasks`, `handlers`, `variables`, `templates`, and `tags`
