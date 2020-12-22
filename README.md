# Kubernetes Ops Playbook

Switch Current Cluster.
```bash
kubectl config use-context <cluster-name>
```
---
```bash
kubectl get nodes
```

```bash
kubectl cluster-info
```

```bash
kubectl apply -f pod.yml
```

```bash
kubectl get pods --watch
```

```bash
kubectl get pods -o wide
```

```bash
describe pods hello-pod
```

```bash
kubectl delete -f pod.yml
```





```bash
kubectl get svc
```

```bash
kubectl get ep
```
---
# Deployment 
## List All Deployment 
```bash
kubectl get deploy
```
## List All Replica Sets
```bash
kubectl get rs
```

```bash
kubectl rollout status deploy <name>
```

```bash
kubectl rollout history deploy <name>
```

```bash
kubectl rollout undo deploy <name> --to-revision=1
```
### Access Container Shell
```bash
kubectl -n <namespace> exec -it <pod-name> sh
```
