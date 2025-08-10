# 0x09. Web infrastructure design

This project focuses on designing web infrastructure for different scenarios, from simple single-server setups to complex distributed systems with security and monitoring.

## Learning Objectives

- Draw diagrams covering web stack infrastructure
- Explain the role of each component in web infrastructure
- Understand system redundancy concepts
- Know acronyms: LAMP, SPOF, QPS

## Tasks

### 0. Simple web stack
Design a one-server web infrastructure hosting www.foobar.com with LAMP stack.

**Requirements:**
- 1 server
- 1 web server (Nginx)
- 1 application server
- 1 application files (codebase)
- 1 database (MySQL)
- 1 domain name foobar.com with www record pointing to server IP 8.8.8.8

### 1. Distributed web infrastructure
Design a three-server web infrastructure for www.foobar.com.

**Requirements:**
- 2 additional servers
- 1 web server (Nginx)
- 1 application server
- 1 load balancer (HAproxy)
- 1 set of application files
- 1 database (MySQL)

### 2. Secured and monitored web infrastructure
Design a secured and monitored three-server infrastructure for www.foobar.com.

**Requirements:**
- 3 firewalls
- 1 SSL certificate for HTTPS
- 3 monitoring clients

## Files

- `0-simple_web_stack` - Simple web stack diagram
- `1-distributed_web_infrastructure` - Distributed web infrastructure diagram  
- `2-secured_and_monitored_web_infrastructure` - Secured and monitored infrastructure diagram

## Author

Team project for ALX System Engineering & DevOps track.