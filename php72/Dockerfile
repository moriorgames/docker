# Build command:
# docker build -t moriorgames/php72-base .
FROM        ubuntu:17.10
MAINTAINER  MoriorGames "moriorgames@gmail.com"

# Install packages
RUN         apt-get update -y && apt-get upgrade && apt-get install -y \
            software-properties-common \
            language-pack-en-base
RUN         LC_ALL=en_US.UTF-8 add-apt-repository ppa:ondrej/php

# Once the PPA is installed, update the local package cache to include its contents:
RUN         apt-get update && apt-get install -y \
            php7.2 \
            php7.2-xml \
            zip \
            vim
