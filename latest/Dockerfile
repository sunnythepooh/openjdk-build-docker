FROM centos:latest
RUN yum-builddep -y java-1.8.0-openjdk
RUN yum install -y hg gcc g++ git
RUN useradd openjdk

USER openjdk
WORKDIR /home/openjdk

RUN [ "/bin/bash" ]
