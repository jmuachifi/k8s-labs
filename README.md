# k8s Labs
## Deploy nginx
```
kubectl apply -f nginx-deploy.yaml
```
## Deploy wordpress
```
kubectl apply -f wordpress-deployment-dev.yaml
```
## Delete deployment
```
kubectl delete -f nginx-deploy.yaml
kubectl delete -f wordpress-deployment-dev.yaml
```
