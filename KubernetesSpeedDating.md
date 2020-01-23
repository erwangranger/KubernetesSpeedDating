# Getting to know K8S

| Number | Command |
|----|------------------------|
| 01 | `which kubectl`          |
| 02 | `kubectl version --short` |
| 03 | `kubectl cluster-info` |
| 04 | `kubectl get nodes` |
| 05 | `kubectl get nodes -o wide` |
| 06 | `kubectl describe node node1 \| more` |
| 07 | `kubectl top nodes` |
| 08 | `kubectl get pods` |
| 09 | `kubectl get pods --all-namespaces \| more` |
| 10 | `kubectl get namespaces` |
| 11 | `kubectl get pods -n monitoring` |
| 12 | `kubectl get pods -n monitoring -o wide` |
| 13 | `kubectl create namespace NordiK8S` |
| 14 | `kubectl get namespaces` |
| 15 | `kubectl get pods -n fumi02 -o wide` |
| 16 | `watch kubectl get pods -n fumi02 -o wide` |
| 17 | `<ctrl-b>, then <">` |
| 18 | `kubectl delete pod sas-viya-programming-0` |
| 19 | `kubectl -n fumi02  scale deployment sas-viya-cas-worker --replicas=5` |
| 20 | `kubectl -n fumi02  scale deployment sas-viya-themeservices --replicas=5` |
| 21 | `kubectl top pods` |
| 22 | `kubectl -n fumi02 delete pod sas-viya-cas-0` |
| 23 | `kubectl taint nodes node5 key=value:NoSchedule` |
| 24 | `kubectl -n fumi02 delete pods --all` |
| 25 | `kubectl taint nodes node5 key=value:NoSchedule-` |
| 25 | `kubectl taint nodes node5 key=value:NoSchedule-` |
