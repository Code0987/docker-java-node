FROM azul/zulu-openjdk-alpine:8-jre@sha256:e77bba25b8c94db028e4b8c31b8d5a83a25a78c9d165ae9ca1a39a61b3959c00
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  git \
  nodejs \
  nodejs-npm \
  yarn \
  curl
