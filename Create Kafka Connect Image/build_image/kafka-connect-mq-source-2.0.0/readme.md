This repo contains a working and tested files to build a Kafka Connect image using an MQ source connector that does not contain the dependency files.

You can download the dependencies from maven central.

| artifactId | groupId | version | Maven Central |
| :--- | :--- | :--- | :--- |
| connect-api | org.apache.kafka | >= 3.4.1 | https://mvnrepository.com/artifact/org.apache.kafka/connect-api |
| connect-json | org.apache.kafka | >= 3.4.1 | https://mvnrepository.com/artifact/org.apache.kafka/connect-json |
| javax.jms-api | javax.jms | >= 2.0.1 | https://mvnrepository.com/artifact/javax.jms/javax.jms-api |
| com.ibm.mq.allclient | com.ibm.mq | >= 9.3.3.1 | https://mvnrepository.com/artifact/com.ibm.mq/com.ibm.mq.allclient |
| slf4j-api | org.slf4j | >= 2.0.7 | https://mvnrepository.com/artifact/org.slf4j/slf4j-api |
| jackson-databind | com.fasterxml.jackson.core | >= 2.14.3 | https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-databind |
| json | org.json | >= 20230618 | https://mvnrepository.com/artifact/org.json/json |
