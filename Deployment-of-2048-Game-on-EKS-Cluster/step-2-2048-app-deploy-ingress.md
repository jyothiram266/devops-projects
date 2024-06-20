# 2048 App

## Create Fargate profile

```
eksctl create fargateprofile \
    --cluster demo-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/jyothiram266/devops-projects/master/Deployment-of-2048-Game-on-EKS-Cluster/2048-Game-deployment.yaml?token=GHSAT0AAAAAACPHENP6UZAJWFRS7UVUNNH4ZTUNVIA
```



![Screenshot 2023-08-03 at 7 57 15 PM](https://github.com/iam-veeramalla/aws-devops-zero-to-hero/assets/43399466/93b06a9f-67f9-404f-b0ad-18e3095b7353)
