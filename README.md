# sprinboot-kafka
This project deals with production and consumption of kafka message


Commands
zookeeper-server-start.bat ../../config/zookeeper.properties     ]==>zookeeper up

kafka-server-start.bat .\config\server.properties ]==>kafka up

kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic test  ] -->create topic

kafka-console-producer.bat --broker-list localhost:9092 --topic test                                    ]--topic listen
kafka-console-consumer.bat --topic test --bootstrap-server localhost:9092 --from-beginning



