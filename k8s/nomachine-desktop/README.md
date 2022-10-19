# Installing nomachine desktop app in k8s

```
kubectl apply -f nomachine.yaml
```

the above command generates nomachine-svc loadbalancer ip. Get the ip of it and open nomachine desktop app and enter <Loadbalancer ip> and port as 4000.

to get the loadbalancer ip execute the below command.

```
kubectl get svc nomachine-svc
```
