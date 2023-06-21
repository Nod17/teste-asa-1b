FROM ubuntu/bind9

RUN apt update

RUN apt upgrade -y

RUN apt install dnsutils -y

COPY ./etc/* /etc/bind

EXPOSE 53/tcp

EXPOSE 53/udp

EXPOSE 953/tcp