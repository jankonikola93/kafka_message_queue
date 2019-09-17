# kafka_message_queue
Message Queue using Kafka and Zookeeper Docker containers

Docker compose file for runing Kafka in Docker container.
Follow this steps to run Kafka:
1. Open PowerShell and clone this repository: https://github.com/jankonikola93/kafka_message_queue.git
    run command: git clone 
2. Change working directory to KafkaMQ:
    run command: cd KafkaMQ
3. Start docker containers:
    run command: docker-compose up -d
    this command will start two containers: broker and zookeeper

Broker container maps host ports 9092 and 29092 to docker ports 9092 and 29092
Zookeeper container maps host port 2181 to docker port 2181
