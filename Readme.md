# DO26 - Comandos usados

## Aula 1

- Instalação do docker: https://docs.docker.com/get-docker/
- Rodando o primeiro container: `docker run hello-world`
- Baixando a primeira imagem: `docker pull php:7.2-apache`
- Inspecionando a imagem: `docker image instpect <ID_DA_IMAGE>`
- Listando os containers: `docker ps -a`
- Limpando o docker (tanto imagens quanto containers): `docker system prune`


## Aula 2

- Rodando a aplicação PHP: `docker run -d --name php001 -p80:80 -v /root/php001/:/var/www/html php:7.2-apache`
