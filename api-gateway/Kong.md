# Kong
- [Kong](#kong)
  - [What problem does **Kong** want to solve](#what-problem-does-kong-want-to-solve)
  - [Advantage](#advantage)
  - [Disadvantage](#disadvantage)
  - [Who does **Kong** compare to](#who-does-kong-compare-to)

[**Kong**](https://github.com/Kong/kong) is the most popular API gateway on github. Official website is [here](https://konghq.com/).

## What problem does **Kong** want to solve

If you are building for the web, mobile, or IoT (Internet of Things) you will
likely end up needing common functionality to run your actual software. Kong
can help by acting as a gateway (or a sidecar) for microservices requests while
providing load balancing, logging, authentication, rate-limiting,
transformations, and more through plugins.

![](https://konghq.com/wp-content/uploads/2018/05/kong-benefits-github-readme.png)

## Advantage

* **High Performance**: Sub-millisecond processing latency to support mission critical use cases and high throughput.
* **Extensibility**: With a pluggable architecture to extend Kong in Lua or GoLang with Kong's Plugin SDK.
* **Portability**: To run on every platform, every cloud and to natively support Kubernetes via our modern Ingress Controller.
- **Cloud-Native**: Platform agnostic, Kong can run on any platform - from bare metal to containers - and it can run on every cloud natively.
- **Kubernetes-Native**: Declaratively configure Kong with native Kubernetes CRDs using the official Ingress Controller to route and connect all L4 + L7 traffic. 
- **Dynamic Load Balancing**: Load balance traffic across multiple upstream services.
- **Hash-based Load Balancing**: Load balance with consistent hashing/sticky sessions.
- **Circuit-Breaker**: Intelligent tracking of unhealthy upstream services.
- **Health Checks:** Active and passive monitoring of your upstream services.
- **Service Discovery**: Resolve SRV records in third-party DNS resolvers like Consul.
- **Serverless**: Invoke and secure AWS Lambda or OpenWhisk functions directly from Kong.
- **OAuth2.0**: Easily add OAuth2.0 authentication to your APIs.
- **Logging**: Log requests and responses to your system over HTTP, TCP, UDP, or to disk.
- **Security**: ACL, Bot detection, allow/deny IPs, etc...
- **Monitoring**: Live monitoring provides key load and performance server metrics.
- **Forward Proxy**: Make Kong connect to intermediary transparent HTTP proxies.
- **Authentications**: HMAC, JWT, Basic, and more.
- **Rate-limiting**: Block and throttle requests based on many variables.
- **Transformations**: Add, remove, or manipulate HTTP requests and responses.
- **Caching**: Cache and serve responses at the proxy layer.
- **CLI**: Control your Kong cluster from the command line.
- **REST API**: Kong can be operated with its RESTful API for maximum flexibility.
- **Geo-Replicated**: Configs are always up-to-date across different regions.
- **Failure Detection & Recovery**: Kong is unaffected if one of your Cassandra nodes goes down.
- **Clustering**: All Kong nodes auto-join the cluster keeping their config updated across nodes.
- **Scalability**: Distributed by nature, Kong scales horizontally by simply adding nodes.
- **Performance**: Kong handles load with ease by scaling and using NGINX at the core.
- **Plugins**: Extendable architecture for adding functionality to Kong and APIs.

## Disadvantage
- Official dashboard is only available for [enterprise](https://konghq.com/products/kong-enterprise). But you can find some unofficial dashboards such as [kong-dashboard](https://github.com/PGBI/kong-dashboard) and [konga](https://github.com/pantsel/konga).

## Who does **Kong** compare to