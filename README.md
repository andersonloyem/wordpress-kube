# wordpress-kube

```
git clone https://github.com/andersonloyem/wordpress-kube.git
cd wordpress-kube
kubectl apply -f ./
kubectl get po,svc,deploy -o wide
kubectl logs pod/mysql-deploy-xxx
kubectl get po,svc,deploy -o wide
```

![image](https://user-images.githubusercontent.com/30845852/119739078-faa35980-be81-11eb-954b-92de02fb82a6.png)

#### monitoring installation : https://ubuntu.com/blog/monitor-your-kubernetes-cluster

https://www.digitalocean.com/community/tutorials/how-to-set-up-a-kubernetes-monitoring-stack-with-prometheus-grafana-and-alertmanager-on-digitalocean

https://docs.microsoft.com/fr-fr/azure/aks/kubernetes-action
