#kube cert manager
Service to manage certificates in kubernetes

## Requires manual deployment with kubectl due to nature of roles needed

```
kubectl create secret generic dns-credentials --from-file dnscred-prod.json --namespace kube-system
kubectl create -f rbac.yaml
kubectl create -f certificate-type.yaml
kubectl create -f claim.yaml
kubectl create -f deployment.yaml

```
