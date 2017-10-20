#kube cert manager
Service to manage certificates in kubernetes

Must integrate with appropriate provider https://github.com/PalmStoneGames/kube-cert-manager/blob/master/docs/providers.md

```
kubectl create -f rbac.yaml
kubectl create -f certificate-type.yaml
kubectl create -f claim.yaml
kubectl create -f deployment.yaml

```

#Use either a certificate or ingress definition
