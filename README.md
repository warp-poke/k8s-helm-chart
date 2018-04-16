# k8s-Helm-chart

Kubernetes chart to deploy Poke stack on k8s:

* Warp10 (in standalone mode)
* Kafka
* Zookeeper
* PostgreSQL

And all Poke components:

* [Poke-API](https://github.com/warp-poke/poke-api)


````bash
helm dependency list
helm dependency update

helm install --name "poke"
````