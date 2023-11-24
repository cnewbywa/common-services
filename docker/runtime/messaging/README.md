# Messaging service
This service provides messaging capabilities to projects that need it.

The project contains the following components:

* [Confluent](https://www.confluent.io/) Community version of [Kafka](https://kafka.apache.org/) with [Zookeeper](https://zookeeper.apache.org/)

Please note that the Docker Compose project mounts volumes to the host file system.

## Usage

* Prerequisites
  * The needed docker network has been created by running `/docker/runtime/network/create-network.sh`

Run the `start-messaging.sh` script.