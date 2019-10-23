FROM  docker.io/nginx

MAINTAINER fengjian <fengjian@senyint.com.com>

RUN rm /etc/nginx/nginx.conf -rf

RUN rm /etc/nginx/conf.d -rf

RUN mkdir /etc/nginx/logs/ -p
RUN mkdir /data/logs/file -p

ADD nginx.conf  /etc/nginx/

ADD vhost.tar.gz /etc/nginx/
