Enable Stop Protection for EC2 Instance
---
why you need protection for ec2 instance:
This prevents accidental API stop actions, not necessarily shutdowns initiated from within the operating system.

Implementation checklist:
--
Steps to Enable Stop Protection (Console):
Open the Amazon EC2 console.
Navigate to Instances and select the instance.
Choose Actions > Instance settings > Change stop protection.
Select Enable.
Click Save.

Note:
--
Error Message: If you try to stop a protected instance, you will receive an error
indicating that the instance has stop protection enabled.
Disabling: To stop the instance, you must first disable this setting by clearing 
the check box in the Change stop protection menu.
