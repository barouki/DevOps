FROM ubuntu:latest

RUN apt-get update && apt-get install -y curl webpack
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
WORKDIR /frontend
COPY frontend .
RUN npm install
CMD npm start