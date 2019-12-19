# Spring Boot Web Application

##Part 6
This repository has the project files for the post SPRING BOOT WEB APPLICATION, PART 6 – SPRING SECURITY WITH DAO Authentication Provider
that is part of the tutorial series on Spring Boot available from by website at [Spring Framework Guru](https://springfrspringframework.guru)

## Checkout the full tutorial here!
[Spring Boot - making Spring Fun again!](https://springframework.guru/spring-boot-web-application-part-1-spring-initializr/)

# My Notes

## Spring Boot Notes

- In the target folder, we have two jars: 
    - .jar - fat jar or uber jar, with ALL maven dependencies
    - .jar.original - our classes
    
## Steps

1. Create temp folder and create Dockerfile file and copy the jar file

2. Write de Docker file

3. Create the image

```
docker build -t spring-boot-docker .
``` 

4. Start a Container