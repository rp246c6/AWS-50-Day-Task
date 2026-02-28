Create AMI from EC2 Instance
--
why to create AMI for EC2 Instance:
Creating an Amazon Machine Image (AMI) for an EC2 instance is essential
to create a reusable template of your server's configuration,
including the OS, installed software, and application data

Checklist for imlementation
--
1) Open the Amazon EC2 console.
2) Select the instance you want to use for the AMI from the Instances section in the navigation pane.
3) Stop the instance (optional but recommended for filesystem consistency): Choose Instance state > Stop instance. The instance will be rebooted during the process if you do not stop it manually or select the "No reboot" option, which may affect data integrity.
4) Create the image: Once the instance is selected, choose Actions > Image and templates > Create image.
5) Configure the image:
Enter a unique Image name and optional Description.
Review and adjust the EBS volumes settings if necessary.
6) Choose Create image

Notes:
It enables rapid scaling, ensures consistent environments,
acts as a backup/disaster recovery solution, and simplifies deploying pre-configured systems
