# Jenkins Project

This project demonstrates a Jenkins server setup integrated with webhooks to trigger jobs and send notifications on any changes.  
It includes different types of Jenkins jobs to showcase various CI/CD approaches.  

---

## 📌 Overview
The project covers:  
- Jenkins server setup  
- Webhook integration for automatic triggers  
- Notifications on repository changes  
- Multiple Jenkins job types  
- Docker container creation with versioned images  

---

## 🛠 Tools & Technologies
- Jenkins  
- Git / GitHub  
- Webhooks  
- Maven  
- Jenkins Pipeline  
- Docker  

---

## ⚙️ Jenkins Job Types Included

### 1️⃣ Freestyle Job
- Basic Jenkins job  
- Used for simple build or test tasks  
- Suitable for beginners  

### 2️⃣ Maven Job
- Builds Java projects using Maven  
- Demonstrates dependency management and build lifecycle  

### 3️⃣ Pipeline Job
- Uses Jenkins Pipeline (Jenkinsfile)  
- CI/CD defined as code  
- Supports complex workflows and automation  

---

## 🔔 Webhook Integration
- GitHub Webhook is configured  
- Any push or change in the repository triggers Jenkins jobs automatically  
- Enables continuous integration  

---

## 🐳 Docker Integration
- The Jenkins pipeline builds the project code and packages it into a **Docker container**.  
- Each build generates a **versioned Docker image**, allowing consistent deployments.  
- The container can then be deployed locally or on any environment supporting Docker/Kubernetes.  

---

## 🚀 Use Cases
- Learning Jenkins fundamentals  
- Practicing CI/CD concepts  
- Comparing different Jenkins job types  
- Demonstrating Jenkins skills for DevOps roles  

---

## 📄 Notes
- This project is for learning and demonstration purposes.  
- Can be extended with:  
  - Docker integration to produce versioned containers  
  - Kubernetes deployment  
  - Slack / Email notifications  
