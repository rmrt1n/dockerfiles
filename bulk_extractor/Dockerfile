FROM kalilinux/kali-rolling:latest
RUN apt update && apt install -y bulk-extractor
WORKDIR /root
ENTRYPOINT ["/usr/bin/bulk_extractor"]

