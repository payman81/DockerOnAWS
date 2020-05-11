# Simple Apache Dockerfile
#
FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update
RUN apt-get install -y apache2
CMD /usr/sbin/apache2ctl -D FOREGROUND
EXPOSE 80
