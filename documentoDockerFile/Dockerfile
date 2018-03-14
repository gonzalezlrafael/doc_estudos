
FROM ubuntu

MAINTAINER Rafael Gonzalez rgonzales.k2@rd.com.br

RUN apt-get -y update

ENV JAVA_VER 8
ENV JAVA_HOME /usr/lib/jvm/java-7-oracle

RUN ifconfig

RUN sudo apt-get install python-software-properties \ 
    sudo add-apt-repository ppa:webupd8team/java \
    sudo apt-get update \ 
    sudo apt-get install oracle-java6-installer


RUN echo "export JAVA_HOME=/usr/lib/jvm/java-7-oracle" >> ~/.bashrc


