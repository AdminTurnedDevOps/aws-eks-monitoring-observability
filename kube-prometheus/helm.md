```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

```
helm repo update
```

```
helm install kube-prometheus -n kube-prometheus prometheus-community/kube-prometheus-stack --create-namespace
```