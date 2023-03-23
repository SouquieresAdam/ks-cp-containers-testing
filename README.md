# ks-cp-testcontainers

This repository try to demonstrate how to leverage [cp-testcontainers](https://github.com/testcontainers-all-things-kafka/cp-testcontainers) 
with a Kafka Streams Application

## Prerequisites to build this code base

- Have a docker environment (required to run the Integration-Test classes)
- Have a local build of the [cp-testcontainers](https://github.com/testcontainers-all-things-kafka/cp-testcontainers) project since it appears to be unavailable on advertised maven repository at the time of the creation of this repositor


This project use some code from https://github.com/confluentinc/kafka-streams-examples/, the two files that I used mention that ownership and their attached Apache 2.0 License

ContainerTestUtils.java which is a simplification of io.confluent.examples.streams.IntegrationTestUtils.java
io.confluent.examples.streams.utils.KeyValueWIthTimestamp is a simple copy paste

