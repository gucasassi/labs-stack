# RabbitMQ Docker Setup

This repository contains a Docker Compose file for setting up and running RabbitMQ in a Docker container. RabbitMQ is an open-source message broker that supports multiple messaging protocols. This setup uses the `rabbitmq:3-management-alpine` image, which includes the RabbitMQ server along with the management UI.

## Prerequisites

Before you begin, ensure you have Docker and Docker Compose installed on your system. If you don't have them installed, follow the instructions on the [Docker website](https://docs.docker.com/get-docker/) and the [Docker Compose documentation](https://docs.docker.com/compose/install/).

## Usage

To use this Docker Compose file.

#### 1. Start the Service

```bash
docker-compose up -d
```

#### 2. Access RabbitMQ UI:

Open your web browser and navigate to http://localhost:15672. The default username and password are `guest`/`guest`.

#### 4. Interacting with RabbitMQ:

You can interact with RabbitMQ using the Management UI or by connecting to it through the default port `5672`.

#### 5. Stopping the Service:

To stop the RabbitMQ container, run:

```bash
docker-compose down
```

Thats all, happy coding!
