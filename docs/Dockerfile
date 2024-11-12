# syntax=docker/dockerfile:1 
FROM nginx:1.27.2-alpine3.20 as deploy
WORKDIR /app
EXPOSE 80
COPY ./app/build ./static/devbox/
COPY ./nginx.conf /etc/nginx/nginx.conf
