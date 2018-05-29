# Docker-Asterisk13Debian
Dockerfile Asterisk 13 in Debian 9

# Descargar imagen
docker pull apariciojuanjose/asterisk13-base

# Como usar esta imagen 
docker run --name asterisk -d apariciojuanjose/asterisk13-base
o
docker run --name asterisk -d -p 5060:5060 apariciojuanjose/asterisk13-base

# Como usar la consola de asterisk una ves corriendo el contenedor
docker exec -ti asterisk asterisk -cvvvvvvvvr

