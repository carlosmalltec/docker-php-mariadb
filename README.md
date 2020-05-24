# docker-php-mariadb
Projeto docker 

# Para uso deste projeto instale e configure o docker
* https://docs.docker.com/compose/install/

# Para facilitar o uso do projeto, existe um arquivo MAKE 
* Comandos make:

* make build  = sudo docker-compose up --build
* make start = sudo docker-compose up -d
* make stop = sudo docker-compose stop
* make show_containers = sudo docker ps
* make connect_php = sudo docker exec -it $(nome_do_container_php) bash
* make connect_nginx = sudo docker exec -it $(nome_do_container_nginx) bash
* make connect_mysql = sudo docker exec -it $(nome_do_container_mysql) bash