Example TICK stack using MALT stack
===================================

This is an example of setting up the TICK stack using the principles of the MALT stack,
primarily Kafka.

For more information, see our blog post:  http://www.maltstack.com/2017/08/setting-up-tick-stack-on-docker.html

To get started, download Docker and run:

```
docker-compose up
```

This will create an entire stack with 3 Zookeeper nodes, 3 Kafka nodes, Grafana, InfluxDB, and
a telegraf publisher and consumer.

Once started, open Grafana at http://localhost:3000
