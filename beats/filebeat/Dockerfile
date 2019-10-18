FROM docker.elastic.co/beats/filebeat:6.5.4

ENV FILEBEAT_VERSION=6.5.4

# config file
ADD filebeat.yml /usr/share/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml