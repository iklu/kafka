zookeeper-server-start.bat C:\APP_INSTALLED\kafka_2.11-0.10.2.0\config\zookeeper.properties


    Download any binary version(I've downloaded kafka_2.11-0.10.2.0) of Kafka from https://kafka.apache.org/downloads
    Extract it to any folder(I've extracted to "C:\Kafka")
    Open Command Prompt
    Go to the folder that you extract Kafka(C:\Kafka\kafka_2.11-0.10.2.0)
    Run this command .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties to start Zookeeper
    Run this command .\bin\windows\kafka-server-start.bat .\config\server.properties to start Kafka
