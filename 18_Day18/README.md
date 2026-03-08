 Create Read-Only IAM Policy for EC2 Console Access
 --
 why to create READ ONLY IAM Policy:
 Creating a read-only IAM policy for EC2 Console access is crucial for implementing the principle of least privilege, 
 which minimizes the security "blast radius" in the event of compromised credentials or human error.

 Checklist for implementing :
1) Sign in to the AWS Management Console and open the IAM console.
2) In the navigation pane, select Policies, and then select Create policy.
3) Switch to the JSON tab and paste the Json policy document.
4) Choose Next.
5) On the Review and create page, enter a Policy name (e.g., EC2ConsoleReadOnlyPolicy) and optionally a description.
6) Choose Create policy.
