# MongoDB Docker Setup

This repository contains a Docker Compose file for setting up and running MongoDB in a Docker container. MongoDB is a popular NoSQL database known for its scalability and flexibility. This setup uses the `mongo:7.0-jammy` image.

## Prerequisites

Before you start, make sure you have Docker and Docker Compose installed on your system. If not, you can find the installation instructions on the [Docker website](https://docs.docker.com/get-docker/) and the [Docker Compose documentation](https://docs.docker.com/compose/install/).

## Usage

To use this Docker Compose file:

#### 1. Start the Service

```bash
docker-compose up -d
```

#### 2. Accessing MongoDB

You can connect to MongoDB at `localhost:27017`.

#### 4. Stopping MongoDB

To stop the MongoDB container, run:

```bash
docker-compose down
```

Thats all, happy coding!
