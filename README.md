# KubernetesDemo

This is a demo of using Kubernetes with .NET Core

To get started, install .NET Core 3.1, then Docker Desktop and enable Kubernetes.  Once done run the following commands to build the app:

```docker build . -t localhost:5000/k8s:1.0```

Then apply the Kubernetes objects in the Kubernetes directory

```
kubectl apply -f 01-namespace.yml
kubectl apply -f 02-service.yml
kubectl apply -f 03-deployment.yml
```
