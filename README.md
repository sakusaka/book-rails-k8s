# book-rails-k8s
kubernetesで、Ruby on Rails環境を構築した

起動方法
```
$ kubectl apply -f .docker/kubernetes/webserver.yml
$ kubectl apply -f .docker/kubernetes/dbserver.yml
```

情報を得る
```
kubectl get all
```

シャットダウン
```
$ kubectl delete -f .docker/kubernetes/webserver.yml
$ kubectl delete -f .docker/kubernetes/dbserver.yml
```