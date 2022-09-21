# Networking and Content Delivery

## Overview 
- Describe the elements of a network
- Describe how common netwokr protocols work
- Understand concepts of Cloud Networks
- Use of the cloud control panel to manage cloud resources 

## What is a Network? 
- Two or more client machines connected to each other.
- Require a network device (i.e router) to connect 
- Purpose: TO communicate and share resources

## LAN vs WAN
- Local Area Network -> Home networks, corporate networks
- Wide Area Network -> The internet/world-Wide Web

## Definitions
- Network devices - physical devices used for communication
- OSI - Open Systems Interconnection; the 7-layer model
- Protocol - the est of rules of algorithms that define communication
- Unique Identifiers - A human-readable name given to each device
- IP Addresses - a 4-Part unique address i.e 192.168.2.6
- CIDR - Classless Inter-Domain Routing ie. 192.0.2.0 /24 
- MAC Address -physical addresss of the device
- Port - a "channel" through which specific data can be sent
- Socket - Combination of IP address and port number
- DNS Server - Domain Name System ( or "server")
- ARP - Addresss Resolution Protocol
- RARP - Reverse Address Resolution Protocol
- THe Internet - A global network of interconnected smaller networks
- URI - Unifrom REsouce  Identifier (or URL) 

## THE OSI (7 Layer) Model
7. Application layer - HUman Computer interaction layer, where applications can access the network services
6. Presentation Layer - Ensures that data is in a usable format and is where data encryption occurs
5. Session Layer - Maintains connections and is responsible for controlling ports and sessions
4. Transport Layer - Transmits data using transmission protocols including TCP and UDP 
3. Network Layer - Decides whjich physical path the data will take
2. Datalink Layer - Defines the format of data on the network
1. Physical Layer - Transmits raw bit stream over the physical Medium 

## Amazon VPC 
- Provision a section of the AAWS Cloud
  - Selection of Ip address ranges
  - creation of subnets
  - Configuration of routing tables and network gateways
  - WE have complete control over the VPC

## Elastic Network Interfaces (ENI's)
- A primary private IPv4 address from the IPv4 address range of your CPV 
- One or more secondary pricate IPv4 addresses frin tge IPv4 
- One Elastic IP address (IPv4) Per private IPv4 addresss
- One public IPv4 address
- One or more IPv6 addresses
- One or more security groups
- A MAC address
- A source/destinatiojn check flag

##  Network Address Translation 
- NAT devices enables instances in a private subnet to conenct to the internet.
- NAT tables are basically DNS servers for PRIVATE networks
- We want to PREVENT the internet from initiatitng contact with these resources
- NAT Gateways
- NAT Instances

## Shared  VPC's 
- Separation of duties
- Ownership 
- Security groups
- Efficiencies
- Optimized costs

## VPC  Peering
- A networking connection between two VPC's 
- Purpose: A private line of communication
- Connect our own VPC 

## Virtual Private Networks
- Definition: A connection from one private network to another private network, using a secure virtual tunnel over the public inter

## AWS Direct Connect
- A dedicated, private network connection between the company network and AWS Resouces
- Does not use the internet
- May Bring greater performance to our AWS

## VPC Endpoints
- ENdpoint Service
- Gateway Endpoint
- Interface ENdpoint

## AWS Transit Gateways
- Defintion: A network transit hub that we can use to interconnect our CPV and onsite networks
