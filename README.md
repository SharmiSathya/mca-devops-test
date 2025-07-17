
## 🚀 Setup Instructions (Minikube)

### 1. Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- Java 21 and Maven (for backend)

### 2. Start Minikube

minikube start
minikube addons enable ingress

kubectl get pods -n ingress-nginx

3. Update /etc/hosts

192.168.49.2 mca.local
(Replace 192.168.49.2 with output of minikube ip)

4. Build & Push Docker Images


   docker build -t backend:latest .
   docker build -t frontend:latest .

5. Deploy to Kubernetes

     kubectl apply -f k8s/

6. Verify Deployment

     kubectl get all -n default
     kubectl describe ingress
