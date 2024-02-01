# SonarQube with PostgreSQL Docker Setup

This repository contains a Docker Compose file for setting up and running SonarQube with a PostgreSQL database in Docker containers. SonarQube is an open-source platform for continuous inspection of code quality.

## Prerequisites

Before you start, ensure you have Docker and Docker Compose installed on your system. If not installed, follow the instructions on the [Docker website](https://docs.docker.com/get-docker/) and the [Docker Compose documentation](https://docs.docker.com/compose/install/).

## Usage

To use this Docker Compose file.

#### 1. Start the Service

```bash
docker-compose up -d
```

#### 2. Access SonarQube

Open your web browser and navigate to http://localhost:9000. Log in with the default credentials (Username: `admin`, Password: `admin`).

#### 3. Configure SonarQube (if necessary)

Follow the on-screen instructions to complete any additional setup.

#### 4. Stopping the Services

To stop the SonarQube and PostgreSQL containers, run:

```
docker-compose down
```

Thats all, happy coding!
