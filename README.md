```deploying node app with Kubernetes```

```ocker build -t hello-node:v1 .```

```ubectl run hello-node --image=hello-node:v1 --port=8080```

```kubectl get deployments```

```kubectl get pods```

```kubectl get events```

```kubectl config view```

```kubectl expose deployment hello-node --type=LoadBalancer```

```kubectl logs <POD-NAME>```

```kubectl delete service hello-node```

```kubectl delete deployment hello-node```
