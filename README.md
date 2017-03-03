# Camunda BPM EE Docker image

## Folder Structure
Folder/File | Description
---|---
./camunda-ee-postgresql | Docker image for PostreSQL incl. Camunda tables
docker-compose.yml | Docker composition that wires all services together

## Running

- Build and run all Docker images using `docker-compose up -d --build`
- View the logs using `docker-compose logs -f`
- Show down all containers and delete all volumes using `docker-compose down -v`

## URLs
- jdbc:postgresql://localhost:5432/camunda (username: camunda, password: camunda)