Enable Internet Access for Private EC2 using NAT Instance
--
why to enable Access for Private Ec2 using NAT Instance

Allows them to access the internet (for patches, updates, or API calls) 
while remaining hidden from direct inbound internet traffic, enhancing security

checklist for implementation:
1) Set Variables
2)Get VPC and Private Subnet IDs
3) Create a Public Subnet
4) Ensure Internet Gateway Exists & Attached
5) Create Route Table for Public Subnet
6) Create Security Group for NAT Instance
7) Launch NAT Instance (Amazon Linux 2)
8) Disable Source/Destination Check
9) Update Private Subnet Route Table
10) Verification.
