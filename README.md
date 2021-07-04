# ticketing
 
### Set Secrets
```
kubectl create secret generic jwt-secret --from-literal=JWT_KEY=<your_jwt_secret>
```

### NATS PORT forwarding
```
kubectl port-forward nats-depl-7cdd497544-56tjr 4222:4222
```