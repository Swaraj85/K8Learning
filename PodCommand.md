# Create Pod
Command: 
```
kubectl run my-nginx --image=nginx:alpine 
```


Descrp: Create "my-nginx" pod from docker image "nginx:alpine"

# Delete pods
Command: 
```
kubectl delete deployment my-nginx 
```
Descrp:
1. Delete the pod with name "my-nginx"
. kubernetes will not bring this pod up becuase deployment was deleted
2. 