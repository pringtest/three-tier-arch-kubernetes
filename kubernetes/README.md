# Kubernetes: Application Deployment

## Introduction 
- Here are the steps to deploy an application into kubernetes cluster


## Deploy Nginx
```sh
kubectl apply -f ./ingress/ingress-nginx.yml
```


## Deploy Applications: Web app and API server
```sh
kubectl apply -f ./app/deployment.yml
```

