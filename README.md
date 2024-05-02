esse compose instala o traefik 2.12 na ultima versão estavel para produção

plataformas 
linux/amd64 	
linux/arm/v6
linux/arm64/v8
cria a rede no docker com o comando 

docker network create --driver=overlay traefik_public
