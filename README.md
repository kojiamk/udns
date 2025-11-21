# UDNS
Anycast DNS Solution with Unbound DNS Resolver
-----------------------------------------------
DNS Resolver setup with Debian 12 and Unbound DNS Resolver
- Interface with Public IP Address for Outgoing DNS Query
- Interface with Private IP Address, Loopback Address & Anycast Addressee for Listening Client DNS Lookup 
- DNSSEC, Performance Tuning, Logging

Anycast Routing setup with Cisco Router
- Interface with Private IP Address to connect DNS Resolver Server 
- IP SLA to check DNS service status
- Track for floating static route
- Static route for forwarding client DNS Lookup to DNS Resolver Server
- Redistribute Anycast DNS addressee to BGP network
