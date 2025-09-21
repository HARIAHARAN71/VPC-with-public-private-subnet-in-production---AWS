# VPC-with-public-private-subnet-in-production---AWS
This example demonstrates how to create a VPC that you can use in a production environment.
To improve resilency , the servers are deployed in two availability zones by using a Auto Scaling Group and Application Load Balancer. For additional security , deploy the servers in private subnets.
The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway
