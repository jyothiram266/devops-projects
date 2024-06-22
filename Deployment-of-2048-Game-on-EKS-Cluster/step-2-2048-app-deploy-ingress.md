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



![Screenshot 2023-08-03 at 7 57 15 PM](https://github-production-user-asset-6210df.s3.amazonaws.com/43399466/258144320-93b06a9f-67f9-404f-b0ad-18e3095b7353.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T175630Z&X-Amz-Expires=300&X-Amz-Signature=5afaa48e64d700fdaddfe6a2cc87a8a454ce2b64d5aeed84d9d09d006d161cc9&X-Amz-SignedHeaders=host&actor_id=112464539&key_id=0&repo_id=655550654)
