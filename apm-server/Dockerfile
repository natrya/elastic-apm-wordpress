FROM docker.elastic.co/apm/apm-server:8.5.3
COPY apm-server.yml /usr/share/apm-server/apm-server.yml
USER root
RUN chown root:root /usr/share/apm-server/apm-server.yml
USER root
