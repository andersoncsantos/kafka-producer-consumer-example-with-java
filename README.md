# Creating Kafka Topic
```
$ docker exec -it <nome da image do kafka no Docker> /bin/bash
```
```
$ cd opt/kafka/bin
```
```
$ ./kafka-topics.sh --bootstrap-server kafka:9092 --create --topic <nome do tópico> --partitions 1 --replication-factor 1
```
