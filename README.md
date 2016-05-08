# Zuul Server

Run this app as a normal Spring Boot app. If you run from this project 
it will be on port 8765 (per the `application.yml`). Also run [eureka server](https://github.com/eacarvalho/spring-cloud-eureka-server.git) and the
[stores](https://github.com/spring-cloud-samples/customers-stores/tree/master/rest-microservices-store) 
and [spring-cloud-netflix](https://github.com/eacarvalho/spring-cloud-netflix.git).  

You should then be able to view json content from 
`http://localhost:7070/hello` and `http://localhost:8765/spring-cloud-netflix/hello` which are
configured in `application.yml` as proxy routes.
