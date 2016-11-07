FROM alpine:edge
MAINTAINER lqf.1996121@gmail.com

RUN apk update && apk add libressl
ADD ./entryrt /usr/local/bin/

CMD ["entrypoint"]
