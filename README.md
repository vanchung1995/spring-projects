# spring-projects
All about Spring include multi modules

All projects use Spring Boot 3.1.1 required Java 17+
You should install `docker` and `docker-compose` first

Run docker file to create mysql run:  
`docker-compose -f third-parties/dockers/docker-compose.yaml up -d
`

The url for mysql:  
`jdbc:mysql://localhost:3306/spring-project?allowPublicKeyRetrieval=true&useSSL=false`