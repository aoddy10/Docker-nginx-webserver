FROM node:8

FROM nginx:alpine
## Remove default nginx website
RUN rm -rf /usr/share/nginx/html/*
## From 'builder' copy website to default nginx public folder
COPY . /usr/share/nginx/html
EXPOSE 80