FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
	apt-transport-https \
	ca-certificates \
	git \
	curl \
	gnupg \
	libnss3 \
	libnss3-tools \
	libfontconfig1  \
	xvfb 

RUN Xvfb :10 -screen 0 1280x720x16 &

RUN apt install -y chromium-browser=71.0.3578.98-0ubuntu0.16.04.1


RUN curl -sL https://deb.nodesource.com/setup_6.x | bash - && apt-get update && apt-get install -y nodejs

RUN npm install -g ember-cli

WORKDIR /usr/src/
