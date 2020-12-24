FROM alpine:latest

ENV PERL5LIB /regripper

RUN apk add --no-cache perl perl-dev git perl-app-cpanminus wget make \
  && cpanm Parse::Win32Registry \
  && git clone https://github.com/keydet89/RegRipper3.0.git /regripper \
  && adduser -D rip \
  && chown -R rip /regripper \
  && cd /regripper \
  && rm -rf .git* *.exe *.bat *.zip \
  && apk del git make

VOLUME /data

USER rip

WORKDIR /regripper

ENTRYPOINT ["perl", "rip.pl"]

