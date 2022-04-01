# kafka_demo

#Config Kafka for Window
//start server
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

.\bin\windows\kafka-server-start.bat .\config\server.properties

//test
.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic test

.\bin\windows\kafka-console-producer.bat --bootstrap-server localhost:9092 --topic demo
