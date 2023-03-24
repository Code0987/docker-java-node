FROM azul/zulu-openjdk-alpine:11-jre@sha256:9df2fac35b8b7ec621d29a9fb52dfe9ddbf075fc47702a831a90cd23b1280e9c
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  git \
  nodejs \
  nodejs-npm \
  yarn \
  curl
