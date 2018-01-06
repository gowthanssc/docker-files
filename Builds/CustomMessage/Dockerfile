# Dockerfile based on the latest centos7 image - non -privileged user entry
FROM centos:latest
MAINTAINER naveendasari571@gmail.com

RUN useradd -ms /bin/bash user
RUN echo "EXPORT 192.168.0.0/24" >> /etc/exports.list

USER user
