FROM debian:stretch

RUN apt-get update && apt-get install -y bind9

RUN rm -rv /etc/bind/*
COPY files/bind /etc/bind

CMD ["/usr/sbin/named", "-g", "-4"]
