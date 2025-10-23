# 🔒 DevSecOps Demo Project

A simple web app securely deployed to AWS using DevSecOps principles.

## Features
✅ Infrastructure as Code (Terraform)  
✅ Static and Dependency Scanning (Bandit, Trivy)  
✅ Container Security  
✅ Automated CI/CD Pipeline (GitHub Actions)  
✅ AWS Deployment (EC2)  

## How to Run
1. Clone this repo  
2. Add GitHub Secrets:
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`
   - `DOCKERHUB_USER`
   - `DOCKERHUB_TOKEN`
3. Push code to `main` branch  
4. GitHub Actions runs automatically  
5. Access the app via the EC2 public IP (port 5000)
