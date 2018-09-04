FROM docker.io/alpine

USER root
RUN apk add nodejs
COPY helloworld.js /
ENTRYPOINT node helloworld.js
