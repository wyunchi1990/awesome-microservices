# Awesome Microservices [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This is a awesome microservices project used to analysis projects about microservices. Four questions will be analysised for each project about microservices: `What problem does this project want to solve`, `Who does this project compare to`, `Advantage`, `Disadvantage`. You can find more index project [here](https://github.com/mfornos/awesome-microservices).

- [Awesome Microservices ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-microservices-img-srchttpscdnrawgitcomsindresorhusawesomed7305f38d29fed78fa85652e3a63e154dd8e8829mediabadgesvg-altawesome)
  - [Frameworks](#frameworks)
  - [Components](#components)
    - [API Gateway](#api-gateway)
    - [Configuration Center](#configuration-center)
    - [Service Discovery](#service-discovery)
    - [Messaging](#messaging)
    - [Logging](#logging)
    - [Monitoring](#monitoring)
    - [Tracing](#tracing)
    - [High Availability](#high-availability)
    - [Security](#security)
    - [Traffic Control](#traffic-control)

## Frameworks

## Components

### API Gateway
As the name says that `API gateway` is the door of the backend. It deliver the requests from client to the right backend server. It has three main functions: `Service routing`, `API version management` and `Load balance`.
### Configuration Center
There are many logic configurations that you don't want bind them with the binary package or docker image. To decoupling the modification of logic configurations and service release. We need to build a configuration center to store the configurations of each service. By using configuration center developers can change the configuration values without *rebuild*, *restart* or *deploy* the service.
### Service Discovery
### Messaging
### Logging
### Monitoring
### Tracing
### High Availability
### Security
### Traffic Control