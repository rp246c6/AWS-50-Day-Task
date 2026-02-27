Attaching ENI to EC2 instance
--
why to attach:
--
Attaching an Elastic Network Interface (ENI) to an EC2 instance provides a virtual network card that enables advanced networking capabilities, such as creating management networks, implementing high-availability failover, and enabling multi-subnet communication.

Implementation checklist:
1) In the Network Interfaces list, select the newly created ENI (status should be "available").
2) Click Actions and select Attach.
3) Select the target Instance ID from the list.
4) Click Attach.

Note:
   An Elastic IP associated with an ENI that is not attached to a running instance will incur charges.
