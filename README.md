# Kubernetes Ops Playbook

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
kubectl get rs
```

```bash
kubectl get deploy
```

```bash
kubectl get svc
```

```bash
kubectl get ep
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

