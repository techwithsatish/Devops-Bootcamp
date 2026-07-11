## CURD COMMANDS
```shell
# create deployement
kubectl create deployement <name>

# edit deployement
kubectl edit deployement <name>

# delete deployement
kubectl delete deployement <name>
```

## status of different k8s component

```shell

kubectl get all

kubectl get nodes

kubectl get pods

kubectl get services

kubectl get deployments

kubectl get replicasets

kubectl get pod --watch

kubectl describe pod <pod-name>

```

## debugging pods

```shell

# LOG to the console
kubectl logs <pod-name>

# Get interactive terminal
kubectl exec -it <pod-name> -- /bin/bash

# Get info about the pod
kubectl describe pod <pod-name>
```
## Use config file for CURD operations

```shell

# Apply config file
kubectl apply -f <file-name>.yaml

# Delete config file
kubectl delete -f <file-name>.yaml
```

## Get the secrets

```shell
# Get all secrets
kubectl get secrets







