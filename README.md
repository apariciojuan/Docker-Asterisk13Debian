# Docker-Asterisk13Debian
Dockerfile Asterisk 13 in Debian 9

# Descargar imagen
docker pull apariciojuanjose/docker-asterisk13debian

# Como usar esta imagen 
docker run --name asterisk -d apariciojuanjose/docker-asterisk13debian
o
docker run --name asterisk -d -p 5060:5060 apariciojuanjose/docker-asterisk13debian

# Como usar la consola de asterisk una ves corriendo el contenedor
docker exec -ti asterisk asterisk -cvvvvvvvvr

