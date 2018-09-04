FROM openjdk:8-jre-alpine

USER root
RUN adduser -S nexus
RUN wget https://download.sonatype.com/nexus/3/latest-unix.tar.gz -O nexus3.tar.gz \
	&& mkdir /opt/ \
	&& tar -xzvf nexus3.tar.gz -C /opt/
ENTRYPOINT /opt/nexus-3.13.0-01/bin/nexus run
