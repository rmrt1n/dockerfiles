FROM kalilinux/kali-rolling:latest

RUN apt update && \
    apt install -y ruby binutils-multiarch && \
    gem install one_gadget

WORKDIR /root

ENTRYPOINT ["one_gadget"]

