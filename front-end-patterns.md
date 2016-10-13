
# Components 

## Reverse Proxy 

A reverse proxy taking requests from the Internet and forwarding them to servers in an internal network. Those making requests to the proxy may not be aware of the internal network.

## Load balancers
## Application Servers
## API Gateway
## DNS Servers
## Cache Servers

# Use cases
## nodejs based web application 
aws route53 with elastic IP + haproxy/nginx + phusion-passenger + nodejs

* buffers the slow clients responses <explain what are slow clients here> 
* provisioning, load balancing, monitoring and auto-scaling the nodejs servers 
* nginx protects/secures the servers from Internet attacks

![](https://pbs.twimg.com/media/CNiUkVdUAAAatdC.png)

deployment on AWS

## Appendix
### [nginx](https://www.nginx.com/products/feature-matrix/)
* A reverse proxy and a load balancer. 
* secures the servers running behing it from various attacks and vulnerables using arbitatary data. 
* buffers responses for slow client.
* can cache http responses
* can serve static content directly
* support web sockets
* terminates SSL/TLS endpoints

### [HAProxy](http://www.haproxy.org/)
* Layer 4 and Layer 7 load balancer (HTTP, TCP, UDP, Mail etc.)
* reverse proxy

### [Phusion Passenger]()
* Application server

