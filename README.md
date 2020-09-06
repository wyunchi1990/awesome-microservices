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
As the name says that `API gateway` is the door of the backend. It deliver the requests from client to the right backend server. It has three main functions: `Authentication`, `Service routing` and `Load balance`.
Project Name                          | Main Language           | Github stars            | Analysis
------------------------------------- | ----------------------- | ----------------------- | -----------------------
[Kong](https://github.com/Kong/kong) | Lua | ![Stars](https://img.shields.io/github/stars/Kong/kong.svg) | [Kong](api-gateway/Kong.md)
[Ocelot](https://github.com/ThreeMammals/Ocelot) | C# | ![Stars](https://img.shields.io/github/stars/ThreeMammals/Ocelot.svg) | [Ocelot](api-gateway/Ocelot.md)
[apisix](https://github.com/apache/apisix) | Lua | ![Stars](https://img.shields.io/github/stars/apache/apisix.svg) | [apisix](api-gateway/apisix.md)
[manba](https://github.com/fagongzi/manba) | Go | ![Stars](https://img.shields.io/github/stars/fagongzi/manba.svg) | [manba](api-gateway/manba.md)
[soul](https://github.com/Dromara/soul) | Java | ![Stars](https://img.shields.io/github/stars/Dromara/soul.svg) | [soul](api-gateway/soul.md)
[goku-api-gateway](https://github.com/eolinker/goku-api-gateway) | Go | ![Stars](https://img.shields.io/github/stars/eolinker/goku-api-gateway.svg) | [goku-api-gateway](api-gateway/goku-api-gateway.md)
[gravitee-gateway](https://github.com/gravitee-io/gravitee-gateway) | Java | ![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-gateway.svg) | [gravitee-gateway](api-gateway/gravitee-gateway.md)
[express-gateway](https://github.com/ExpressGateway/express-gateway) | Javascript | ![Stars](https://img.shields.io/github/stars/ExpressGateway/express-gateway.svg) | [express-gateway](api-gateway/express-gateway.md)
[tyk](https://github.com/TykTechnologies/tyk) | Go | ![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk.svg) | [tyk](api-gateway/tyk.md)
[janus](https://github.com/hellofresh/janus) | Go | ![Stars](https://img.shields.io/github/stars/hellofresh/janus.svg) | [janus](api-gateway/janus.md)
[orange](https://github.com/orlabs/orange) | Lua | ![Stars](https://img.shields.io/github/stars/orlabs/orange.svg) | [orange](api-gateway/orange.md)
[ambassador](https://github.com/datawire/ambassador) | Python | ![Stars](https://img.shields.io/github/stars/datawire/ambassador.svg) | [ambassador](api-gateway/ambassador.md)
[microgateway](https://github.com/strongloop/microgateway) | Javascript | ![Stars](https://img.shields.io/github/stars/strongloop/microgateway.svg) | [microgateway](api-gateway/microgateway.md)


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