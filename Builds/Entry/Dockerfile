# Dockerfile based on the latest centos7 image - non -privileged user entry
FROM centos:latest
MAINTAINER naveendasari571@gmail.com

RUN useradd -ms /bin/bash user

ENTRYPOINT echo "This command will display this message on EVERY container that is run from it"

USER user
