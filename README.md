# kafka-learning


## Downloads

```
https://www.apache.org/dyn/closer.cgi?path=/kafka/3.5.0/kafka_2.13-3.5.0.tgz
https://dlcdn.apache.org/kafka/3.5.0/kafka_2.13-3.5.0.tgz

```

```
bin\windows\zookeeper-server-start.bat config\zookeeper.properties
bin\windows\kafka-server-start.bat config\server.properties
bin\windows\kafka-topics.bat --create --topic user-topic --bootstrap-server localhost:9092
bin\windows\kafka-console-producer.bat --topic user-topic --bootstrap-server localhost:9092
bin\windows\kafka-console-consumer.bat --topic user-topic --from-beginning --bootstrap-server localhost:9092
```
