FROM kalilinux/kali-rolling:latest

RUN apt update \
  && apt install python python-dev git pcregrep libpcre++-dev -y \
  && git clone https://github.com/volatilityfoundation/volatility.git \
  && cd /volatility

VOLUME /data

WORKDIR /volatility

ENTRYPOINT ["python", "vol.py"]

