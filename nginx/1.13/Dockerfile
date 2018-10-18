FROM nginx:1.13-alpine

MAINTAINER JG <julien@mangue.eu>

ADD vhost.conf /etc/nginx/conf.d/default.conf
ADD hzs.conf /etc/nginx/conf.d/hzs.conf
ADD doc.conf /etc/nginx/conf.d/doc.conf
ADD lumu.conf /etc/nginx/conf.d/lumu.conf
ADD mic.conf /etc/nginx/conf.d/mic.conf

WORKDIR /var/www
