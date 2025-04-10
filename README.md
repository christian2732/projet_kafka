Kafka + ELK Stack Docker Project

![Kafka-ELK-Stack](https://img.shields.io/badge/Stack-Kafka%20%2B%20ELK-blue)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED)

Déploiement local d'un pipeline de données avec Apache Kafka et la stack Elastic (Elasticsearch, Logstash, Kibana) via Docker Compose.

 Services Déployés

| Service       | Port  | Description                          |
|---------------|-------|--------------------------------------|
| Zookeeper     | 2181  | Coordination des nœuds Kafka         |
| Kafka         | 9092  | Broker Kafka pour streaming de données |
| Elasticsearch | 9200  | Moteur de recherche et d'indexation  |
| Kibana        | 5601  | Visualisation des données            |
| Logstash      | 5044  | Traitement des flux de données       |

 Prérequis

- Docker 20.10+
- Docker Compose 2.5+
- 4GB de RAM minimum (8GB recommandé)

 Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/kafka-elk-docker.git
   cd kafka-elk-docker
