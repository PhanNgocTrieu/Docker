FROM ubuntu:20.04

COPY /home/trieupn/Documents/_git/Cpp_Challenge /tmp/

RUN apt-get update && apt-get install -y build-essenstial libsocket++1 libsocketcan++-dev libsocketcan2 chrpath socat cpio python python3 python3-pip python3-pexpect xz-utils debianutils iputils-ping python3-git python3-jinja2 libegl1-mesa libsdl1.2-dev xterm bison flex curl libssl-dev libcurl4-openssl-dev libtool autotools-dev automake gettext bc xutils-dev autopoint intltool gperf xsltproc libxml2-utils xml-core docbook-xsl gnome-doc-utils kmod && curl -sL https://deb.nodesource.com/setup_14.x | bash - && apt-get update && apt-get install -y nodejs && npm install -g typescript && useradd -mU -s /bin/bash build >> /home/build/.bashrc

CMD su build2
