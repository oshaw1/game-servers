# game-servers
Repository containing various game servers, majority of which use docker / docker-compose for easy portability

## Space-engineers
`docker-compose up -d`

## Project Zomboid

## Minecraft

### Docker command to reverse engineer images
`docker history <IMAGE_NAME> --no-trunc --format json | jq --slurp . | jq -r 'reverse | .[].CreatedBy'`
