FROM alpine:3.1

MAINTAINER vSense <docker@vsense.fr>

RUN apk add --update \
    openvpn \
    curl \
    && rm -rf /var/cache/apk/*

COPY run.cmd /usr/bin/run

ENTRYPOINT ["/usr/bin/run"]
