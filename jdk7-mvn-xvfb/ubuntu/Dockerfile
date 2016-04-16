FROM maven:3.3.9-jdk-7

RUN apt-get -y update && apt-get -y install xvfb nodejs npm \
 && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
