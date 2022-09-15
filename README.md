# docker-wordpress-db-phpmyadmin
Meu Docker de Start de Desenvolvimento

Esse arquivo contém 2 diretórios e o arquivo de início do Docker docker-compose.yml o primeiro diretório é o app-data onde contém os arquivos que possivelmente vai para public_html e o bd-data que possivelmente é o banco de dados, não são arquivos de restore, e sim o sistema do mysql, porém na migração é necessário um dump.

# Alguns comandos importantes
- docker ps
Listar os containers que estão rodando

- docker ps -a
Listar os container que não estão rodando

- docker stop [id]
Pára o container

- docker rm [id]
Remove/Apaga um container

#Subir container
- docker compose up -d
