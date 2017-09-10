FROM centos:latest
RUN yum install -y file which unzip nano
RUN yum-builddep -y java-1.8.0-openjdk
RUN yum install -y hg git compat-gcc-44 compat-gcc-44-c++ compat-glibc-headers-2.12 
#For AOT
RUN yum install -y elfutils-libelf-devel
RUN useradd openjdk

USER openjdk
WORKDIR /home/openjdk

RUN [ "/bin/bash" ]
