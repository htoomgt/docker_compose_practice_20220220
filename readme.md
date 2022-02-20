# Docker Compose In 12 Minutes

To study docker compose with simple small microservice project.

## Steps to up and running  project

Assume the docker compose is already installed.

- `copy .env.example .env` to use the environment variable
- `sudo docker-compose --env-file ./.env up -d` to start the service using dotenv file and  run in background
- `sudo docker-compose ps` to check the running container
- `sudo docker-compose down` to shutdown the container and remove

## Referenced Link

- Youtube video tutorial [link](https://www.youtube.com/watch?v=Qw9zlE3t8Ko)