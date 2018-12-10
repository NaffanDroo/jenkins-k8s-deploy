# jenkins-k8s-deploy
kubernetes deployment files for Jenkins

## How to install
```
kubectl apply -f namespace.yaml
kubectl apply -f secrets.yaml -n jenkins
kubectl apply -f test.yaml -n jenkins
```
