# Springboot-buildpacks-docker
This project is an example for how to leverage Cloud-native buildpacks support in Spring Boot 2.3.1 to containerize Spring Boot App without Dockerfile

#### Command to Dockerize the Spring Boot and craete Docker Image:
````
mvn spring-boot:build-iamge
````

#### Command To run docker image 
````
docker run -p 8080:8080 springbootbuildpack:0.0.1-SNAPSHOT  
````
