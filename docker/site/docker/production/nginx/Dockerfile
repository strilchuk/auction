FROM nginx:1.17-alpine

COPY ./site/docker/development/nginx/conf.d /etc/nginx/conf.d

WORKDIR /app

COPY ./site/public ./public