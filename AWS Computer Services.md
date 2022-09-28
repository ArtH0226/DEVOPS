NOTES 06: COMPUTE CIT 114 Arturo Hernandez
# AWS Compute Services

## Overview 
- AWS Computing Resources (EC2) 
  - Operating Systems (Windows & Linux)
  - Virtualataion

## Operating Systems
- The MOST IMPORTANT software that runs on a computer
- Manages the computer's memory & processess
- Manages the computer's hardware and software
- Use the computer's CPU, memory and storage
- Use batch processes & background programs 
- Main desktop OS's: Microsoft, OS-X (Apple), Linux
- Main mobile OS's: IOS, Android
- Designed to be easy-to Use

## Operating Systems, cont.
-  Controlling the hardware: Drivers
-  32bit vs 64bit CPU's 
-  OS's usually come pre-loaded on your computer
-  Open-Source vs proprietary 

## AWS Operating Systems
- Supported EC2 Operating Systems
  - Linux
   - Linux on AWS Marketplace
    - CentOS, Red Hat, Debain, Etc.
   - Amazon Linux 2
 - Windows Server (not regular Windows)
 - Raspbian

## AWS Compute Services
- Virtual Machines - AWS Elastic Cloud COmputer (EC2)
- Serverless -AWS Lambda
- Containers
  - AWS Elastic Container
  - AWS Elastic Kubernetes
  - AWS Fargate
  - AWS Elastic Container Registry
- Platform as a Service - AWS Elastic Beanstalk 

## Choosing the Right Service
- Evauluate the available computer options
- Understand the available computer configuartaion options
- Collect computer-related metrics
- Determine the required configuration by right-sizing
- Use the available elasticity of resources
- Re-evaluate compute needs based on metrics

## What ARE Virtual Machines
- Definiton: VM's are computers that run inside of other computers using a process called Virtualization. They are often used for purposes of testing, backing up data, or running SaaS applications.
- Operating System: manages the computer's hardware and other software in ways that are useful to the user.
- HypervisorL: the software, firmware, or hardware that VM's run on
- Two or more OS's on one computer
- Purposes of VM's 
  - Testing apps in different environments
  - Running software designed for a different OS 
  - Running outdated software
  
  ## Features & Terminology of EC2 
  - Virtual computing environments, known as instances
  - Preconfigured templates for your instances, known as Amazon Machine Images (AMIs) 
  - Various configuratiojn of CPU, memory, storage, and networking capacity for your instances, known as instance types
  - Secure login information for your instances using key pairs
  - Storage voumes for tempoary data

- Persistent storage volumes for your data using Amazon Elastic Block Store (amazon EBS), known as Amazon EBS volumes
- Multiple Physical locations for your resources, such as instances and Amazon EBS Volume, known as Regions and availabiliy zones
- A firewall that anables you to specify the protocols 

## Key Benefits of EC2 
- Elastic Web-Scale Computing 
- Completely Controlled
- Flexible Cloud Hosting Services
- Integrated
- Reliable
- Secure
- Inexpensive
- Easy to Start 

## Instance Types
- General Purpose
- Computer Optimized 
- Memory Optimized
- Accelerated Computing
- Storage Optimized 

## Amazon Machine Images (AMI) 
- Pre-configured virtual machines with an ever-growing list of operating systems
- Provides the information required to launch an instance
- Includes:
  - EBS snapshots Lunahc permissions
  - Block device mapping
## EC2 Pricing
- On Demand
- Spot instance
- Dedicated Host
- reserved Instance
- Dedicated Instance
- Scheduled Reserved Instances
- Savings Plans
- Free Tiers

## Four Pillars of Cost Optimizations
- Pillar 1: Right Size
- Pillar 2: Increase elasticity
- Pillar 3: Leverage the right pricing model
- Pillar 4: Optimize storage
 
 ## Containers
 - The Code of an application is bundled with configurations and dependencies

- Advantages of a container in cloud computing: 
  - Consistency in cloud storage Application Version Control
  - Efficiency in the operational Activities


## Docker and Kubernetes
- Docker 
  - Lightweight, standalone, exectubale package
  - Includes code, runtie, system, tools, Libraries, and settings
  - Available for both Windows and Linux-based systems

- Kubernetes
  - Open-sourced
  - Manages a cluser

## Containers vs Virtual Machines
- Virtual machines requires a hypervisor: containers can run on the OS.
- Using a container would consume much less resources than a VM

## AWS Container Services
- Amazon Elastic Container Server (ECS_
- Amaon Elastic Kubernetes service (EKS)
- Amazon Elastic Container Registry (ECR)

## Serverless Computing
- write & deploy code without worrying about teh underlying infrastrucutre
- cost benefits/ backend services 
  - Web hosting services
  - database services
  - just executing the app
  
## AWS Lambda
- Bring your own code
- Completely automated administration
- build-in fault tolerance
- ochestrate multiple functions
- only pay fo what you use

## AWS Elastic Beanstalk
- AWS compute service option that usilizes PaaS in order to faciliatte the quick deplyoment, scaling and mangement of our web applications and services.
- The only thing we HAVE to manage is our code/
- Benefits include: Fast and simple to use
- Developer Productivity Impossible to outgrow
- Complete Resource Control


