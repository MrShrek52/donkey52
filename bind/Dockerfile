FROM rockylinux:9
RUN dnf install bind -y
RUN mkdir -p /var/named/master/
RUN chown:named -R /var/named/master
EXPOSE 53/udp