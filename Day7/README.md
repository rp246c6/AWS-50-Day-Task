Change EC2 instance type
--
why Change EC2 instance type was introduced :
The ability to change an Amazon EC2 instance type was introduced to provide flexibility, 
cost optimization, performance tuning, and scalability without requiring users to build new infrastructure from scratch

checkist for implementation
--
1) Stop: Navigate to the EC2 console, select your instance, and choose Instance State > Stop instance.
2) Modify: With the instance stopped, select Actions > Instance settings > Change instance type.
3) Update & Start: Select the new type and click Apply, then select Instance State > Start instance.
4) Verify: Check the instance details to confirm the change.

Notes:
--
It allows users to adapt their virtual server's resources to the dynamic and evolving demands of their
