Attach Elastic IP to EC2 Instance
--
Why EIP is attached to EC2 instance
Elastic IP (EIP) is attached to an EC2 instance to provide a static, 
persistent public IPv4 address that does not change when an instance is stopped, started, or restarted. 

checklist:
1) Select the Elastic IP address.
2) From the Actions dropdown menu, choose Associate Elastic IP address.
3) On the "Associate Elastic IP address" page:
4) For "Resource type", select Instance.
5) In the "Instance" dropdown, select the EC2 instance ID you want to assign the EIP to.
6) Verify the association.
   
Note:
EIPs are free only while associated with a running instance. Unused or disassociated EIPs incur hourly charges
When you stop/start a normal instance, it gets a new IP. An EIP fixes this issue
