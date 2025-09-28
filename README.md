# System Engineering and Infrastructure Concepts

This document summarizes key concepts and resources related to networking, servers, DNS, load balancing, monitoring, databases, and system reliability.  

---

## Networking and Servers

### Network Basics
- Covers how devices communicate over a network.
- Includes concepts like IP addresses, TCP/UDP, and ports.
- Foundation for understanding all other infrastructure topics.

### Server
- A machine or process that provides services to clients.
- Examples include web servers, database servers, and file servers.

### Web Server
- Software such as Apache or Nginx.
- Serves static files and routes traffic to applications.

### Web Server vs Application Server
- **Web Server**: Handles HTTP requests and serves static content.
- **Application Server**: Runs backend logic, processes requests, interacts with databases.
- Often used together in a system.

---

## DNS and Load Balancing

### DNS (Domain Name System)
- Translates domain names (example.com) into IP addresses.
- Enables users to access services without remembering IP numbers.

### DNS Record Types
- **A**: Maps domain to an IPv4 address.
- **AAAA**: Maps domain to an IPv6 address.
- **CNAME**: Alias for another domain.
- **MX**: Mail exchange server.
- **TXT**: Miscellaneous information (such as SPF records, verification).

### Load Balancer
- Distributes incoming traffic across multiple servers.
- Prevents overload on a single machine.
- Improves availability and reliability.

---

## Reliability and High Availability

### Single Point of Failure
- A component whose failure brings down the entire system.
- Should be avoided in system design.

### Avoiding Downtime During Deployment
- Use strategies such as rolling updates, blue/green deployments, or canary releases.
- Load balancers are often used to manage traffic during deployments.

### High Availability Clusters
- **Active-Active**: All nodes handle traffic simultaneously.
- **Active-Passive**: One node is active while others are on standby for failover.

---

## Monitoring and Security

### Monitoring
- Tracking uptime, performance, and errors.
- Provides alerts when issues arise.
- Tools include Nagios, Prometheus, and Grafana.

### HTTPS
- Secure version of HTTP using TLS/SSL.
- Provides encryption, authentication, and integrity for data in transit.

### Firewall
- Filters incoming and outgoing network traffic based on rules.
- Can operate at network or application level.

---

## Databases

### What is a Database
- A system for storing, retrieving, and managing data.
- Can be structured (SQL) or unstructured (NoSQL).

---
