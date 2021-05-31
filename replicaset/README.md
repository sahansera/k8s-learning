```bash
kubectl create -f replicas.yml
kubectl scale replicaset myapp-replicaset replicas=3
kubectl edit rs myapp-replicaset
```

