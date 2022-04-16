# Creating Kafka Topic
```
$ docker exec -it <kafka image name> /bin/bash
```
```
$ cd opt/kafka/bin
```
```
$ ./kafka-topics.sh --bootstrap-server kafka:9092 --create --topic <topic name> --partitions 1 --replication-factor 1
```
