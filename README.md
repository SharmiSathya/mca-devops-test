 docker build -t backend:latest .
 docker build -t frontend:latest .


 kubectl apply -f k8s/

 kubectl get all -n default
 kubectl describe ingress
