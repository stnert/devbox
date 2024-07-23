# syntax=docker/dockerfile:1 
FROM nginx:1.26.1-alpine3.19 as deploy
WORKDIR /app
EXPOSE 80
COPY ./app/build ./static/devbox/
COPY ./nginx.conf /etc/nginx/nginx.conf
