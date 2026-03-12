Setting Up an Application Load Balancer for an EC2 Instance
--
why to set up ALB for Ec2 instance:
The ALB acts as a single point of contact for clients and distributes incoming traffic to healthy EC2 instances. 
It is essential for building highly available, scalable, and secure applications.

checklist for implementation:
1) Create Security Group for ALB (devops-sg).
2) Create Target Group (devops-tg).
3) Create Application Load Balancer (devops-alb).
4) Update EC2 Security Group.
