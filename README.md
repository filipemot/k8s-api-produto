## KubeDev - Kubedev.io
Semana Kubedev - Kubernets


**Criação de Cluster**
kind create cluster --name multinode --config kind-cluster.yaml 

**Aplicação**
kubectl apply -f .\k8s-api-produto\ -R
kubectl get pods
kubectl get service
  

**Testando aplicação**
http://localhost:8080/api-docs
