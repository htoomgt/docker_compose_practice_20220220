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
- Docker Compose run [link](https://docs.docker.com/compose/reference/run/)
- Lara Dock docker compose usage [link](https://laradock.io/getting-started/#Usage)
- Automatically remove container after usage [link](https://serverfault.com/questions/750175/docker-compose-option-to-automaticaly-remove-container-after-run-in-docker-comp)
- Depends on option [link](https://medium.com/@yudapramad/how-depends-on-work-in-docker-compose-89f8afa6d6a0)
- Docker compose networking [link](https://runnable.com/docker/docker-compose-networking#:~:text=Docker%20Compose%20sets%20up%20a,other%20container%20on%20the%20network.)
- Network bridge and overlay [link](https://www.edureka.co/community/101298/what-the-difference-between-bridge-network-overlay-network#:~:text=Bridge%20networks%20are%20usually%20used,to%20communicate%20with%20each%20other.)