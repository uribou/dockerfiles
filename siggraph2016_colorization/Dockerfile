# Start with Ubuntu base image
FROM ubuntu:14.04

# Torch7
FROM kaixhin/torch

# Install wget
RUN apt-get install -y wget

# Run siggraph2016_colorization download model script
RUN git clone https://github.com/satoshiiizuka/siggraph2016_colorization.git /root/siggraph2016_colorization && \
  cd /root/siggraph2016_colorization && \
  ./download_model.sh

# Change working directory
WORKDIR /root/siggraph2016_colorization