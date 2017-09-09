FROM centos:latest
RUN yum-builddep -y java-1.8.0-openjdk
RUN yum install -y hg git compat-gcc-44 compat-gcc-44-c++ compat-glibc-headers-2.12
RUN useradd openjdk

USER openjdk
WORKDIR /home/openjdk

RUN [ "/bin/bash" ]
