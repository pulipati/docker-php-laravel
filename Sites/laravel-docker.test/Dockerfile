FROM node:latest

WORKDIR /d/Learn/docker-php-laravel/home/server

RUN npm install -g json-server

COPY db.json /d/Learn/docker-php-laravel/home/server/db.json

ENTRYPOINT ["json-server", "db.json"]

