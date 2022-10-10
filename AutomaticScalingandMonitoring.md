### Class 12: Automatic Scaling and Monitoring

## Objectives
- Monitor cloud systems and applications
- Solve common business problems using appropriate Information Technology application and systems.
- Use a cloud control panel to create and manage cloud resources

## Topics:
- Monitoring with CloudWatch
- Alarms and Alerts
- Elastic Load Balancing 
- Application Load Balancing
- Network Load Balancing
- EC2 auto scaling
- AWS auto scaling

## Questions to Consider: 
- What kind of monitoring service is available at AWS? 
- Is it possible to be notified when problems occur with applications?
- Can automated solutions be set in place for applications that are overloaded?
- Can the load balancer perform decryption and authentication?
- can we track user authentications when problems occur?
- How complicated is it to set up automatic scaling?

## Monitoring with CloudWatch
- Get alerts when things go wrong
- View metrics for where resources are being allocated
- Create our own dashboards
- Create events based on monitoring
- Set alarms based on usage, or money spent

## CloudWatch Terminology
- Namespace
- Metrics
- Statistics
  - Minimum
  - Maximum
  - Sum
  - SampleCount
  - Average
- Dimensions
- Units of measurement
- Timestamp
- Time Range (Period)
- Alarms
  - OK 
  - Alarm
  - Insufficient
  - Data
- Events

## Elastic Load Balancing
- Load Balancing -> Spreads out network traffic among multiple servers
- Also provides redundancy -> One server goes down, no break in services
- Most AWS Services are offered with a "built-in" reundancy... EXCEPT for EC2!!

- Options:
  - Application Load Balancer (ALB)
  - Netowkr Load Balancer (NLB)

- ELB is Redundant
- EC2 Health Checks
- Other features: 
  - SSL/ TLS/ Traffic Decryption
  - IPv4 or v6 support
  - Dynamic Port mapping
  - Connection draining
  - Cross-AZ support
  - User authentication

## Application + Network Load Balancing
- Distributes incoming traffic across ultiple EC2 instances
- Listener -> Checks for connection requests from clients, and forwards requests to a target group
- Target Group -> Where the requests go
- Difference between ALB/ NLB:

## Auto Scaling
- EC2 auto scaling -> Allows us to launch or terminate instanced controlled by Cloudwatch alarms/ Metrics include auto-scale group metrics such as the minimum and maximum group size and the in-service, pending, standby, and total instances/
- AWS auto scaling -?> Supports services outside fo EC2, including databse services.
