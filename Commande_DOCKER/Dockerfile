#Installation de mon OS : Ubuntu
FROM ubuntu:latest
#Auteur de l'image et version des modifications
LABEL autor="jonathanbriat"
LABEL version="1.0"

#Installation des paquets et dépendances sur le ubuntu
RUN apt update
RUN apt-get -y upgrade
#installation redis en ligne de commande
RUN apt -y install redis
#installation de VIM
RUN apt-get -y install vim
#Installation de python
RUN apt-get -y install python3 python3-pip

#Port utilisé
EXPOSE 8080

#C'est cans ce dossier local de la machine que les sources seront installées.
ADD . /app/
#Les commandes lancées seront toutes exécutées depuis ce repertoire .
WORKDIR /app
