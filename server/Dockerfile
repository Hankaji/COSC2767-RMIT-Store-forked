FROM node:23-alpine

WORKDIR /server

COPY package.json /server/
RUN npm install

COPY . /server/
