# Comand to run the Kubernetes Cluster

## Application of Dashboard adminuser 
```
kubectl apply -f dashboard-adminuser.yaml​
```
## Apply Cluster role 
```
kubectl apply -f cluster_role_binding.yaml\
```
## Creating Pod

```
kubectl apply -f .\createPod.yaml
```

## Creating replica set 
```
kubectl apply -f createReplicaSet.yaml
```
## Creating deployemnt file 
```
kubectl apply -f createDeployment.yaml
```
## Comand to access the API 
```
http://localhost:8001/api/v1/namespaces/default/pods/myreplicaset-hfnx8/proxy/
```

