# 📘 **Azure Containers & Serverless**

---

## 1️⃣ **Azure Kubernetes Service (AKS)**

* Managed Kubernetes cluster service
* Deploy, scale, and manage containerized apps
* Handles **node scaling, upgrades, monitoring** automatically
* Integrates with **Azure Container Registry (ACR)**

**Hands-On:**

* Create AKS cluster
* Deploy a sample containerized app
* Scale pods & test rolling updates

---

## 2️⃣ **Azure Container Instances (ACI)**

* Run containers **without managing VMs**
* Lightweight, fast startup, pay-per-second billing
* Ideal for **short-lived jobs** or **microservices**

**Hands-On:**

* Deploy a container image from Docker Hub or ACR
* Test connectivity and logs

---

## 3️⃣ **Azure Container Registry (ACR)**

* Private container registry (like AWS ECR)
* Store and manage Docker images
* Integrates with **AKS**, **ACI**, **DevOps pipelines**

**Hands-On:**

* Push a Docker image to ACR
* Pull the image in AKS or ACI

---

## 4️⃣ **Azure App Service (Containerized Apps)**

* PaaS for running web apps in **Docker containers**
* Auto scaling, custom domains, TLS/SSL
* Can run Linux or Windows containers

**Hands-On:**

* Deploy a containerized app to App Service
* Configure environment variables & scaling

---

## 5️⃣ **Azure Functions (Serverless)**

* Event-driven, serverless compute
* Triggers: HTTP, Timer, Blob Storage, Event Grid, Service Bus
* Pay only for execution time
* Integrates with **Azure DevOps, Logic Apps, Storage, Cosmos DB**

**Hands-On:**

* Create an HTTP-trigger Function
* Integrate with Storage or Cosmos DB
* Test and monitor execution

---

## 6️⃣ **Azure Logic Apps (Optional)**

* Low-code serverless workflows
* Connect multiple services (SaaS + Azure)
* Example: Blob upload → trigger Function → send email

**Hands-On:**

* Create a simple workflow: HTTP request → store data in Blob → notify via email

---

## 7️⃣ **Event-Driven Architecture Services**

* **Event Grid** → Event routing between Azure services
* **Service Bus** → Reliable messaging & queues
* **Event Hub** → Big data streaming

**Hands-On:**

* Trigger a Function via Event Grid on blob creation
* Send/receive messages in Service Bus queue

---

This set gives you a **complete container + serverless ecosystem** in Azure, mapping directly to your **AWS + DevOps experience** (EKS → AKS, Fargate → ACI, Lambda → Functions).

---
