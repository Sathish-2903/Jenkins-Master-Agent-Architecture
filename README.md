# 🚀 CI/CD Pipeline using Jenkins Master-Agent Architecture (DevOps Project)

## 📌 Project Overview
This project demonstrates the implementation of a **CI/CD (Continuous Integration and Continuous Deployment) pipeline** using **Jenkins Master-Agent architecture**, **Docker**, and **AWS EC2**.

The pipeline automates the process of building, packaging, and deploying a web application (FoodExpress UI) with minimal manual intervention.

---

## 🎯 Objectives
- Implement CI/CD pipeline using Jenkins  
- Understand Jenkins Master-Agent architecture  
- Automate build and deployment processes  
- Use Docker for containerization  
- Deploy application on AWS EC2  
- Gain practical DevOps experience  

---

## 🧰 Tech Stack
- ☁️ AWS EC2 (Cloud Infrastructure)  
- 🔁 Jenkins (CI/CD Automation)  
- 🐳 Docker (Containerization)  
- 🌐 Nginx (Web Server)  
- 💻 HTML, CSS (Frontend Application)  
- 🔗 GitHub (Version Control)  

---

## 🏗️ Architecture
The project follows a DevOps pipeline:

Developer → GitHub → Jenkins Master → Jenkins Agent → Docker Build → EC2 Deployment → Browser Output

---

## ⚙️ Implementation

### 🔹 Day 1
- Created AWS EC2 instances (Master & Agent)
- Configured security groups (Ports: 22, 80, 443, 8080)
- Installed Jenkins using Docker
- Connected Jenkins Agent via SSH
- Created and containerized web application

### 🔹 Day 2
- Created Jenkins pipeline job
- Automated Docker build and deployment
- Executed CI/CD pipeline successfully
- Verified deployment through browser

---

## 🔄 CI/CD Pipeline Flow
1. Developer pushes code to GitHub  
2. Jenkins pulls latest code  
3. Docker image is built  
4. Container is deployed on EC2  
5. Application is served via Nginx  
6. Output is accessed through browser  

---

## 🖼️ Output
- Jenkins pipeline executed successfully ✅  
- Docker container running successfully ✅  
- Application deployed on AWS EC2 ✅  
- FoodExpress UI accessible via browser ✅  

---

## 📸 Screenshots
(Add your project screenshots here)

---

## ⚠️ Challenges Faced
- Jenkins setup using Docker  
- Agent connection via SSH  
- AWS security configuration  
- Docker container errors  
- Pipeline debugging  

---

## 📊 Results
The CI/CD pipeline was successfully implemented and automated.  
The FoodExpress web application was deployed on AWS EC2 and verified through browser access.

---

## 🚀 Future Enhancements
- Integrate Kubernetes for orchestration  
- Add monitoring tools (Prometheus, Grafana)  
- Use Terraform for Infrastructure as Code  
- Improve pipeline automation  

---

## ⭐ Conclusion
This project demonstrates real-world DevOps practices using Jenkins, Docker, and AWS.  
It improves deployment speed, reduces manual effort, and ensures reliable delivery.
README.md
