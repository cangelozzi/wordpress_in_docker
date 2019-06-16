# Wordpress container in Docker

- wordpress
- phpmyadmin
- mysql

#### run file with 
`docker-compose up -d`

#### check container with 
`docker ps`

#### kill all container with
`docker kill $(docker ps -q)`

or

`docker-compose rm`

#### restart composer after a CTRL/C or a `docker-compose stop`
`docker-compose restart`

==========================================

Visit http://localhost:8000 to install Wordpress

Visit http://localhost:8080 to login inside PhpMyAdmin (root password)
- work in progress