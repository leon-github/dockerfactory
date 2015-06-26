# version: 0.0.1
FROM ubuntu:14.04
MAINTAINER Leon Cui "leon.cui@outlook.com"
ENV REFRESHED_AT 2015-06-26



RUN apt-get update
RUN apt-get -y -q install nginx

RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/

EXPOSE 80
