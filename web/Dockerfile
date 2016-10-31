FROM alpine:edge
MAINTAINER Ryo Tanaka <ryo.tanaka@mytrax.co.jp>

RUN apk add --no-cache python

COPY index.html /srv/index.html
WORKDIR /srv

EXPOSE 5000

CMD python -m SimpleHTTPServer 5000


