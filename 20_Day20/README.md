Create IAM Role for EC2 with Policy Attachment
--
why to create IAM Role for EC2 with Policy attached.
provides secure, temporary credentials for applications 
to access AWS services (like S3 or DynamoDB) without hardcoding long-term keys

Implementation checklist
1) Sign in to the AWS IAM console.
2) In the navigation pane, choose Roles, and then choose Create role.
3) For Select trusted entity, choose AWS service.
4) Under Use case, select EC2 from the list of services and then choose Next. This automatically sets up a trust policy allowing the EC2 service (ec2.amazonaws.com) to assume the role.
5) On the Add permissions page, select the check box for the required permissions policy (e.g., AmazonS3ReadOnlyAccess or AmazonSSMManagedInstanceCore). Use the search bar to filter the policies.
6) Choose Next.
7) On the Review page, enter a meaningful Role name (e.g., S3ReadOnlyRole-EC2) and a description.
   Choose Create role
