# Dockerfile

FROM node:lts-alpine

RUN mkdir /client
WORKDIR /client
COPY package*.json ./
RUN npm i
COPY public public
COPY src src

CMD npm start
