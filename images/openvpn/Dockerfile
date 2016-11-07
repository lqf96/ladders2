FROM lqfdocker/http451:base
MAINTAINER lqf.1996121@gmail.com

RUN apk update && apk add openvpn
ADD ./entrypoint /usr/local/bin/

EXPOSE 1194/udp
