# Getting Started

Make sure to run "minikube start" first.

Create service and deployment
```
kubectl create -f deployment.yaml
```

Open minikube dashboard
```
minikube dashboard
```

Connect Kubernetes cluster to local machine
```
minikube tunnel
```

Open browser at `localhost:8080/video`
