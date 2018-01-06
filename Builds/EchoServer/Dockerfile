# Dockerfile based on the latest centos7 image - non -privileged user entry
FROM centos:latest
MAINTAINER naveendasari571@gmail.com

RUN useradd -ms /bin/bash user

CMD "echo" "This is a custom container message for our Naveen Dasari Class"

USER user
