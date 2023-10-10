1. Install Minikube for local Kubernetes cluster.

````
$ minikube start

$ kubectl create configmap logstash-config --from-file=logstash-configmap.yaml

$ kubectl apply -f elasticsearch.yaml
$ kubectl apply -f logstash.yaml
````