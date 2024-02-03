## Steps to install

- configure docker-compose.yml
- rename .env.example to .env
- configure .env


##For first time only !

docker compose up -d
docker compose exec php bash
composer setup

##From the second time onwards

docker compose up -d
docker compose exec php bash


- docker-compose exec php composer setup

- 127.0.0.1:8000
