FROM ubuntu:latest

RUN apt update && apt install -y git wget unzip git openjdk-11-jre iverilog

ENV VNC_RESOLUTION="1920x1200x16" \
    VNC_DPI="96"

COPY menu /root/.fluxbox/menu

RUN wget https://github.com/hneemann/Digital/releases/latest/download/Digital.zip
RUN unzip Digital.zip
RUN mv Digital /usr/local/Digital
COPY Digital.sh /usr/local/Digital
RUN chmod a+x /usr/local/Digital/Digital.sh

WORKDIR /LC3_realized
RUN wget https://github.com/ucrdrk/LC3_realized/releases/download/v1.0.0/LC3_realized-1.0.0.zip
RUN unzip LC3_realized-1.0.0.zip

