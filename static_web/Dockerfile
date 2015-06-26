# version: 0.0.1
FROM ubuntu:14.04
MAINTAINER Leon Cui "leon.cui@outlook.com"
ENV REFRESHED_AT 2015-06-25
RUN apt-get -qq update
RUN apt-get install -y nginx
RUN echo 'Hi, I am in your container' > /usr/share/nginx/html/index.html
EXPOSE 80
