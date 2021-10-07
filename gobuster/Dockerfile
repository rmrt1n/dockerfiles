FROM kalilinux/kali-rolling:latest

RUN apt update \
  && apt install gobuster -y \
  && wget 


WORKDIR /root

ENTRYPOINT ["/usr/bin/steghide"]

