FROM alpine:latest
RUN apk add bind
RUN mkdir -p /var/named/master/
RUN chown:named -R /var/named/master
EXPOSE 53/udp