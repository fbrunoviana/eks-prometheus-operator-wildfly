```
aws eks update-kubeconfig --name demo --region us-east-1
kubectl apply -k wildfly-k8s/overlays/staging
```