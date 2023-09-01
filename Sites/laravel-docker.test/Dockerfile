FROM node:latest

WORKDIR /d/Learn/docker-php-laravel/home/server

RUN npm install -g json-server

COPY db.json /d/Learn/docker-php-laravel/home/server/db.json

COPY alt.json /d/Learn/docker-php-laravel/home/server/alt.json
EXPOSE 3000

ENTRYPOINT ["json-server","--host","0.0.0.0"]

CMD ["db.json"]

