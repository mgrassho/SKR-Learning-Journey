## Discovering Kubernetes

### STEPS

#### Interacting with the Kubernetes API via Kubectl

```
kubectl get pods
```

```
kubectl get pods --namespace my-namespace
```

```
kubectl get services
```

```
kubectl get replicasets
```

```
kubectl get deployments
```

```
kubectl create -f my-pod.yaml
```

```
kubectl create -f https://raw.githubusercontent.com/SAP-samples/
kyma-runtime-learning-journey/main/unit_1/my-pod.yaml
```

```
kubectl apply -f my-pod.yaml
```

```
kubectl delete pod my-pod
```

```
kubectl describe pod my-pod
```

```
kubectl describe pod my-pod -o yaml > my-pod.yaml
```

```
kubectl label pod my-pod my-label=my-value
``
```