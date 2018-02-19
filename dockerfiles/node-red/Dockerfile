FROM nodered/node-red-docker
MAINTAINER Thebora Kompanioni

RUN npm install node-red-contrib-sqldbs
RUN npm install node-red-node-rbe

CMD ["/usr/sbin/mosquitto", "-c", "/mqtt/config/mosquitto.conf"]