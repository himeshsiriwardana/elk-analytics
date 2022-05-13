ARG ELASTIC_VERSION

FROM docker.elastic.co/beats/filebeat:${ELASTIC_VERSION}

USER root
# ADD ./config/filebeat.yml /usr/share/filebeat.yml
RUN mkdir /usr/share/logs_loc
RUN chmod 777 /usr/share/logs_loc