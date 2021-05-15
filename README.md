<h2>Bootcamp Banco Inter Digital Innovation One: Criando um sistema de orçamento, utilizando CQRS, Quarkus, Kafka e deploy no EKS </h2>

Baseado no projeto [cqrs-quarkus-kafka](https://github.com/wesleyfuchter/cqrs-quarkus-kafka) e [java-kubernetes](https://github.com/sandrogiacom/java-kubernetes.git)

Este projeto automatiza o deploy [cqrs-quarkus-kafka](https://github.com/wesleyfuchter/cqrs-quarkus-kafka) em um cluster kubernetes local a partir de um docker-compose.yml utilizando o [kompose](https://kompose.io/) e [minikube](https://minikube.sigs.k8s.io/docs/)

Para fazer o deploy execute os seguintes comandos:
```bash
chmod +x deploy
./deploy
```
Requisitos:

* Java 8
* Gradle 6.2.2
* Minikube
* Kompose
