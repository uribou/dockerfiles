# Torch7
FROM kaixhin/torch

# Install wget
RUN apt-get install -y wget

# Run siggraph2016_colorization download model script
RUN git clone https://github.com/satoshiiizuka/siggraph2016_colorization.git /root/siggraph2016_colorization
WORKDIR /root/siggraph2016_colorization
RUN ./download_model.sh