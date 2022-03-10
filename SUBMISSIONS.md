Michael Arana 1254076

# DOCKER
- [5 pts] Your dockerfile. Please provide a link to this file rather than a screen capture.  
[link_to_dockerfile](spring-petclinic/blob/master/Dockerfile)  
- [5 pts] Your running docker instance as shown by a ps command.
![docker ps_command](figures/docker_DOCKER_PS.png)  
- [5 pts] Your browser accessing the main page of the website from your local container.
![docker web access OK](figures/docker_ACCESS_WEB_OK.png)  

# DOCKER COMPOSE - MYSQL ONLY
- [5 pts] The output from the docker-compose up command.
![mysql only compose up 01](figures/docker_mysql_only_COMPOSE_UP_01.png)  
![mysql only compose up 02](figures/docker_mysql_only_COMPOSE_UP_02.png)  
- [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.
![mysql only Vet page OK](figures/docker_mysql_only_VET_OK.png)  
- [5 pts] A section of the stack trace generated when you attempt to run the application
container that has been updated to use MySQL.
![mysql only stack trace](figures/docker_mysql_only_COMM_EXCEPTION.png)  

# DOCKER COMPOSE - APP SERVER AND MYSQL
- [5 pts] Your updated docker-compose.yml file containing the application server, built from
your local Dockerfile, and the existing MySQL configuration. Please provide a link
to this file rather than a screen capture.  
[link_to_docker-compose.yml](spring-petclinic/blob/master/docker-compose.yml)  
- [5 pts] Your updated application-mysql.properties file containing the URL change for
the database server. Please provide a link to this file rather than a screen capture.  
[link_to_application-mysql.properties](spring-petclinic/blob/master/src/main/resources/application-mysql.properties)  
- [5 pts] The output from the docker-compose up command.
![docker compose up result 01](figures/docker_appServer_mysql_COMPOSE_UP_01.png)  
![docker compose up result 02](figures/docker_appServer_mysql_COMPOSE_UP_02.png)  
- [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container.  
![appServer Vet page OK](figures/docker_appServer_mysql_VET_OK.png)