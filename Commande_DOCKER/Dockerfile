#Installation de mon OS : Ubuntu
FROM ubuntu:latest
#Auteur de l'image et version des modifications
LABEL autor="jonathanbriat"
LABEL version="1.0"

#Installation des paquets et dépendances sur le ubuntu
RUN apt update
RUN apt-get -y upgrade
#installation Kali Linux en ligne de commande
RUN apt -y install redis
#installation de VIM
RUN apt-get -y install vim
#Installation de python
RUN apt-get -y install python3 python3-pip

ADD . /app/
WORKDIR /app
