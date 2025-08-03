
# 🚀 Spring PetClinic Kubernetes Deployment on AWS EC2

This project demonstrates how to deploy the [Spring PetClinic](https://github.com/spring-projects/spring-petclinic) application on a Minikube-based Kubernetes cluster hosted on an AWS EC2 instance. 
It includes setup of Docker, Minikube, Maven, and Java 17 for building and running the app inside Kubernetes.

## 📁 Repository being used as a reference:---

https://github.com/techiescamp/kubernetes-projects

## 🧰 Prerequisites:----

- AWS Account
- Ubuntu EC2 instance (t2.medium or larger recommended)
- Security Group with the following inbound rules:
  - **SSH (22)**
  - **HTTP (80)**
  - **HTTPS (443)**
  - **TCP (8080)**
  - **TCP (30000–32767)** for Kubernetes NodePort

---

## ⚙️ Setup Instructions

### 1️⃣ Create EC2 Instance & Configure Security Group

Launch a new EC2 instance with the necessary inbound rules listed above.


### 2️⃣ Install Docker, kubectl, and Minikube


# Verify everything

### 3️⃣ Install Java 17 & Maven

### 4️⃣ Clone & Build Spring PetClinic App

### 5️⃣ Deploy Application to Kubernetes

Follow the detailed steps in this repository to deploy using Kubernetes:
👉 [techiescamp/kubernetes-projects](https://github.com/techiescamp/kubernetes-projects)

---

### 6️⃣ Port-Forward the Service

Expose the application outside the cluster:
### 7️⃣ Access the Application

Visit your application in a browser:

http://<EC2-PUBLIC-IP>:8080


## ✅ Outcome

You’ll have a fully working Spring Boot application deployed on Kubernetes inside an EC2-hosted Minikube cluster, with external access enabled via NodePort or port-forwarding.

---

## 📌 Notes

* Make sure your EC2 instance has enough resources (min 2 vCPU, 4GB RAM).
* Always verify that ports are open via EC2 Security Group.
* Ensure Docker is running before starting Minikube.

---

## 🙌 Credits

* [Spring PetClinic](https://github.com/spring-projects/spring-petclinic)
* [techiescamp/kubernetes-projects](https://github.com/techiescamp/kubernetes-projects)


