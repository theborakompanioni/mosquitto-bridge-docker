FROM eclipse-mosquitto:1.4.12
MAINTAINER Thebora Kompanioni

#RUN mkdir -p /mqtt/config /mqtt/data /mqtt/log
#COPY config /mqtt/config
#RUN chown -R mosquitto:mosquitto /mqtt
#VOLUME ["/mqtt/config", "/mqtt/data", "/mqtt/log"]

CMD ["/usr/sbin/mosquitto", "-c", "/mqtt/config/mosquitto.conf"]