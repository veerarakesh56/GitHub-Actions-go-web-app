# Install EKS

Please follow the prerequisites doc before this.

## Install a EKS cluster with EKSCTL

```
eksctl create cluster --name demo-cluster --region ap-south-1
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region ap-south-1
```
