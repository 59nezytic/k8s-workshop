# example-voting-app_k8s

```
  $ kubectl create ns vote
```


```
  $ kubectl create -f example-voting-app_k8s/k8s-specifications/
deployment "db" created
service "db" created
deployment "redis" created
service "redis" created
deployment "result" created
service "result" created
deployment "vote" created
service "vote" created
deployment "worker" created
```
