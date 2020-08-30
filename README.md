# spring-boot-skeleton
It's a personal spring boot application configured to be used as skeleton.

##### How to build an image and run the app to this repo
Access the project's directory. For exemple :

`cd my-directory/spring-boot-skeleton ` 

run 

`docker build -t springio/spring-boot-skeleton-docker . `

and 

`docker run
 --name my-app-dockerized
 -p 8080:8080
 springio/spring-boot-skeleton-docker`.
 
 To check if it's OK access http://localhost:8080
 
##### Spring Boot version 
2.3.3.RELEASE

#### Spring boot projects used in this repository
Actuator


