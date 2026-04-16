🚀 EKS Deployment Project

📌 Project Overview

This project demonstrates how to deploy an application on **Amazon EKS (Elastic Kubernetes Service)** using DevOps best practices. It covers containerization, Kubernetes manifests, and deployment automation.

The goal of this project is to showcase **end-to-end deployment of an application on Kubernetes (EKS)**.

---

🏗️ Architecture

* Application Containerized using Docker
* Deployed on Kubernetes Cluster (EKS)
* Managed using kubectl
* Cloud Infrastructure on AWS

---

🧰 Tech Stack

* AWS (EKS, EC2, IAM)
* Kubernetes
* Docker
* kubectl
* GitHub

---
⚙️ Prerequisites

Make sure you have:

* AWS Account
* AWS CLI configured
* kubectl installed
* eksctl (optional)
* Docker installed

---
🚀 Setup & Deployment Steps

1️⃣ Clone Repository

bash
git clone https://github.com/Nazeem-repos/EKS_DEPLOYMENT.git
cd EKS_DEPLOYMENT

---

2️⃣ Create EKS Cluster (if not created)

bash
eksctl create cluster --name my-cluster --region ap-south-1

---

3️⃣ Configure kubectl

bash
aws eks --region ap-south-1 update-kubeconfig --name my-cluster


---

4️⃣ Deploy Application

bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml


---

5️⃣ Verify Deployment

bash
kubectl get pods
kubectl get services

---

📊 Project Structure

EKS_DEPLOYMENT/
│── deployment.yaml
│── service.yaml
│── README.md

---

📸 Output (Add Screenshots Here)

* Running Pods
* Service URL
* Application UI

---

🔄 CI/CD Enhancement (Future Scope)

* Integrate Jenkins pipeline
* Automate Docker build & push
* Auto-deploy to EKS

---

💡My Contributions

* Configured Kubernetes deployment manifests
* Deployed application on AWS EKS
* Managed cluster using kubectl
* Implemented scalable container deployment

---

📚 Learnings

* Kubernetes deployment & services
* EKS cluster management
* Container orchestration
* DevOps workflow for cloud deployment

---

🤝 Contributing

Feel free to fork and improve this project.

---

📜 License

This project is for learning and demonstration purposes.

---

👤 Author

Nazeem Pasha
GitHub: https://github.com/Nazeem-repos
