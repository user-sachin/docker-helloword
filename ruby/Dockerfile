FROM docker.io/alpine

USER root
RUN apk add ruby
COPY helloworld.ruby /
ENTRYPOINT ruby helloworld.ruby
