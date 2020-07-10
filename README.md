A simple kubernetes deployment yaml config. Uses Jacob Alberty's work  to setup a unifi controller on single node clusters with recommended settings and persistant local volumes to work across reboots

Update the volumes specification unify-deployment.yaml to point to your local directories.

```
microk8s.kubectl apply -f ./unify-deployment.yaml 
```

