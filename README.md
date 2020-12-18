# Kubernetes Ops Playbook

``kubectl get nodes``

``kubectl cluster-info``
``kubectl apply -f pod.yml``
``kubectl get pods --watch``
``kubectl get pods -o wide``
``describe pods hello-pod``
``kubectl delete -f pod.yml``
``kubectl get rs``
``kubectl get deploy``
``kubectl get svc``
``kubectl get ep``
``kubectl rollout status deploy <name>``
``kubectl rollout history deploy <name>``
``kubectl rollout undo deploy <name> --to-revision=1``
