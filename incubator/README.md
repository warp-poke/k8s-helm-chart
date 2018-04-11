# k8s-Helm-chart

Kubernetes chart to deploy Poke stack on k8s:

* Warp10 (in standalone mode)
* Kafka
* Zookeeper

````bash
helm dependency list ./poke/
helm dependency update ./poke/

helm install ./poke/ --name "poke"
````