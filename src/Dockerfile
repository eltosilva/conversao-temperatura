# syntax=docker/dockerfile:1

FROM node:9.7
WORKDIR /app
COPY ./package.json .
RUN npm i
COPY . .
CMD [ "node", "server.js" ]