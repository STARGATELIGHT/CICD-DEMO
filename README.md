# CI/CD Pipeline Demo

This repository demonstrates a CI/CD (Continuous Integration & Continuous Deployment) pipeline for automating the build, testing, and deployment of applications. The pipeline is designed to streamline DevOps workflows using best practices.

#Features

-Automated 'Build & Testing' 
- Continuous **Integration with GitHub/Jenkins**  
- Seamless **Deployment to Cloud/Kubernetes/Docker**  
-'Infrastructure as Code Terraform (IaC)' for automated infrastructure provisioning  
- Integration with 'SonarQube for Code Quality' and 'Security Scans'
- Rollback strategy for 'zero-downtime deployments' 

# Prerequisites

Before setting up the CI/CD pipeline, ensure you have:

- "Git" installed (`git --version`)
- "Docker" installed (`docker --version`)
- **Kubernetes (kubectl)** installed (`kubectl version --client`)
- **Terraform (if using IaC)** installed (`terraform --version`)
- **Jenkins/GitHub** configured
- **SonarQube (Optional)** for code quality analysis
- **AWS credentials** (if deploying to the cloud)

#Setup Instructions

## 1  "Clone the Repository"
```sh
git clone https://github.com/STARGATELIGHT/CICD-DEMO.git
cd CICD-DEMO

