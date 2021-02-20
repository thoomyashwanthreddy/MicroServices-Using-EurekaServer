# MicroServices-Using-EurekaServer

## Eureka Server and Discovery Client

Eureka Server is an application that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server. And all the Microservices that register into the discovery are called Discovery Clients.

### Application.properties

eureka.client.registerWithEureka = false
eureka.client.fetchRegistry = false
server.port = 8761
