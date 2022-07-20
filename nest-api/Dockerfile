FROM node:12.14.0-alpine3.11


RUN apk add --no-cache bash

RUN yarn global add -g @nestjs/cli@7.5.6

COPY . .

EXPOSE 3000

USER node

WORKDIR /home/node/app