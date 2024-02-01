# Zookeeper and Kafka Docker Setup

This repository contains a Docker Compose file for setting up and running Zookeeper and Kafka in Docker containers. Zookeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. Kafka is a distributed streaming platform.

## Prerequisites

Before starting, ensure you have Docker and Docker Compose installed on your system. You can find installation instructions on the [Docker website](https://docs.docker.com/get-docker/) and the [Docker Compose documentation](https://docs.docker.com/compose/install/).

## Usage

To use this Docker Compose file:

#### 1. Start the Service

```bash
docker-compose up -d
```

#### 2. Accessing Zookeeper

Zookeeper is accessible on port `2181`.

#### 3. Accessing Kafka

Kafka is accessible on ports `9092` for external connections, `29092` for Docker internal connections, and `9999` for JMX.

#### 4. Stopping the Services

To stop the Zookeeper and Kafka containers, run:

```
docker-compose down
```
