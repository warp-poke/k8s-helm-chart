# k8s-Helm-chart

Kubernetes chart to deploy Poke stack on k8s:

* Warp10 (in standalone mode)
* Kafka
* Zookeeper
* PostgreSQL

````bash
helm dependency list
helm dependency update

helm install --name "poke"
````