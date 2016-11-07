FROM lqfdocker/http451:base
MAINTAINER lqf.1996121@gmail.com

RUN apk update && apk add nghttp2 python
ADD ./entrypoint /usr/local/bin/

EXPOSE 443/tcp
