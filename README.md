# Ambiente Linux distro ubuntu:21.10 com PHP:7.4-fpm, Nginx, Mysql e Phpmyadmin;

## Com Docker e docker-compose instalados baixar os arquivos e rodar o comando docker-compose up -d quando finalizar acessar em seu navegador http://127.0.0.1:8085; 

### Em ambientes linux usar sudo para executar as aplicações.

### Comandos básicos para containers:
#### docker ps => mostra os containers ativos;
#### docker ps -a => mostra todos os containers ativos e inativos;
#### docker rm [nome_container] => deleta container inativo;
#### docker rm -f [nome_container] => deleta container mesmo que esteja ativo;

### Comandos básicos para Images:
#### docker images => Mostra todas as imagens já instaladas;
#### docker rmi [nome_da_imagem] => Apaga a imagem;
#### docker image prune -a => Apaga as imagens que não estão sendo utilizadas por containers ativos;

#### mais informações acessar: https://docs.docker.com/

