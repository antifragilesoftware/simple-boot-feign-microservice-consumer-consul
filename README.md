# Sample Spring Boot Service that consumes another service through Feign and Consul

## To Build into Docker using Maven

First make sure you're running in an environment that has docker available to you. Then execute:

$ ./mvnw package docker:build

Once completed you will have an antifragilesoftware/simple-boot-feign-microservice-consumer-consul image available, as seen by executing:

$ docker images

```
REPOSITORY                                                      TAG                 IMAGE ID            CREATED             SIZE
antifragilesoftware/simple-boot-feign-microservice-consumer-consul                      latest              39fc873649d9        3 seconds ago       667.6 MB
```





