docker compose up -d docker-compose.yml


docker pull mysql:5.7
docker run -d --name mysql57 -p 2808:3306 -e MYSQL_ROOT_PASSWORD="" -e MYSQL_ALLOW_EMPTY_PASSWORD=true mysql:5.7


docker images
docker ps
