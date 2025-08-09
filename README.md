# RailTailProd

This repository contains the configuration for running **RailTail** using Docker Compose.

## Prerequisites
- [Docker](https://docs.docker.com/get-docker/) installed on your system.
- [Docker Compose](https://docs.docker.com/compose/install/) installed.

## Pull the Latest Image
To pull the latest image from the repository, run:
```bash
docker compose pull
```

## Start the Project
After pulling the latest image, start the project in detached mode:
```bash
docker compose up -d
```

## Access the Application
Once the project is running, you can access the RailTail application at:
- **URL**: http://localhost:3000

## Stop the Project
To stop the project, run:
```bash
docker compose down
```

## View Logs
To view the logs of the running containers:
```bash
docker compose logs
```

To follow the logs in real-time:
```bash
docker compose logs -f
```