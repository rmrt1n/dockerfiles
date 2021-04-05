FROM alpine:latest

RUN apk add --no-cache john
RUN mkdir /usr/share/wordlists

COPY rockyou.txt /usr/share/wordlists

WORKDIR /root

ENTRYPOINT ["/usr/bin/john"]

