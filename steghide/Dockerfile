FROM kalilinux/kali-rolling:latest

RUN apt update && apt install steghide -y

WORKDIR /root

ENTRYPOINT ["/usr/bin/steghide"]

