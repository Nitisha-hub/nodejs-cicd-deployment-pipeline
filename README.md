# Node.js CI/CD Pipeline using AWS

## 📌 Project Overview

This project demonstrates a simple CI/CD pipeline for deploying a Node.js application automatically using AWS services.

Whenever code is pushed to GitHub, the pipeline automatically builds and deploys the application to an EC2 instance.

---

## 🚀 AWS Services Used

- AWS CodePipeline
- AWS CodeBuild
- AWS CodeDeploy
- Amazon EC2
- IAM
- GitHub

---

## 🎯 Project Objective

Automate application deployment using CI/CD concepts.

---

## 🛠️ Project Architecture

GitHub → CodePipeline → CodeBuild → CodeDeploy → EC2

---

## 📂 Project Files

| File Name | Purpose |
|------------|----------|
| app.js | Main Node.js application |
| package.json | Node.js project configuration |
| buildspec.yml | Build instructions for CodeBuild |
| appspec.yml | Deployment instructions for CodeDeploy |

---

## ⚙️ Steps Performed

1. Created a Node.js application
2. Uploaded project to GitHub
3. Launched EC2 instance
4. Installed Node.js and CodeDeploy agent
5. Created CodeBuild project
6. Configured CodeDeploy
7. Created CodePipeline
8. Enabled automatic deployment on every GitHub push

---

## ▶️ Running Application

Application runs on:

http://EC2_PUBLIC_IP:3000

---

## 📸 Screenshots

Add project screenshots inside the `screenshots` folder.

Example:
- Pipeline Success
- Build Success
- Deployment Success
- Application Output

---

## ✅ Outcome

Successfully implemented a CI/CD pipeline for automated deployment of a Node.js application using AWS Developer Tools.

---

## 👩‍💻 Author

Nitisha Mali
