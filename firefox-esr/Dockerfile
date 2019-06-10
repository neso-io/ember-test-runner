FROM node:10
# We need wget to set up the PPA, Xvfb to have a virtual screen and unzip to extract ChromeDriver
RUN apt-get update && apt-get install -y firefox-esr xvfb



RUN npm install -g ember-cli

WORKDIR /usr/src/
