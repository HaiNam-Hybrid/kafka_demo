# kafka_demo

#Config Kafka for Window

//start server

D:\Java-Projects\kafka_2.13-3.1.0>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

D:\Java-Projects\kafka_2.13-3.1.0>.\bin\windows\kafka-server-start.bat .\config\server.properties

//test

D:\Java-Projects\kafka_2.13-3.1.0>.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic test

D:\Java-Projects\kafka_2.13-3.1.0>.\bin\windows\kafka-console-producer.bat --bootstrap-server localhost:9092 --topic demo
