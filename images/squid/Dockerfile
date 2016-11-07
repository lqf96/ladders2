FROM lqfdocker/http451:base
MAINTAINER lqf.1996121@gmail.com

RUN apk update && apk add squid
ADD ./entrypoint /usr/local/bin/

EXPOSE 3128/tcp
