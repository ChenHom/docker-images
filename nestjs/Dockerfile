FROM node:19-alpine

ARG WWWGROUP

WORKDIR /app

ENV TZ=UTC

RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apk add git && npm i -g @nestjs/cli

EXPOSE 3000

