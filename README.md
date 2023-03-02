
# Credit Card Fraud Detection

A brief description of what this project does and who it's for


## Deployment

Before starting the kafka server we need to start the zookeeper server first :

```bash
  nohup bin/zookeeper-server-start.sh config/zookeeper.properties >> nohup.out &
```

Increasing the heap size to start kafka server.

```bash
  export KAFKA_HEAP_OPTS="-Xmx256M -Xms128M"

```
Now starting kafka server :

```bash
  nohup bin/kafka-server-start.sh config/server.properties >> nohup.out &
```
Creating kafka topic :

```bash
  C:\Users\Asus>aws configure
  AWS Access Key ID [****************HJGN]:***********
  
```

