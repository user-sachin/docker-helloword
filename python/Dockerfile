FROM docker.io/alpine

USER root 
RUN apk add python
COPY helloworld.py /
ENTRYPOINT python helloworld.py 
