Configuring a Private RDS Instance for Application Development
--
why to configure private RDS Instance for application Developement.
--
It isolates the database from the public internet, enhancing security by preventing unauthorized access.

Checklist for Implementation:
1) Set Variables.
2)Get Default VPC ID.
3)Get Subnets in Default VPC.
4)Create DB Subnet Group.
5)Create Security Group for RDS.
6)Create the RDS Instance.
7)Wait Until AVAILABLE.
8)Validate the RDS instance state.
