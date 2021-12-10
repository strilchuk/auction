FROM nginx:1.17-alpine

COPY ./site/docker/production/nginx/conf.d /etc/nginx/conf.d

WORKDIR /app

COPY ./site/public ./public