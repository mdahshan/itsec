#Docker image for IT Security labs

FROM imunes/template:latest
LABEL maintainer "Mostafa Dahshan <mdahshan@csu.edu.au>"

RUN apt-get update \
    && apt-get install -y socat \
    && apt-get install -y firefox-esr \
    && apt-get install -y sylpheed \
    && apt-get install -y curl \
    && apt-get install -y dsniff \
    && apt-get install -y nmap \
    && apt-get purge --auto-remove \
    && rm -rf /var/lib/apt/lists/* /tmp/*
