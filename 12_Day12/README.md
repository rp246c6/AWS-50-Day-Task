Attach Volume to EC2 instance
--
why to attach:
--
Attaching an EBS volume to an Amazon EC2 instance provides persistent,
scalable, and high-performance block-level storage that survives instance termination

Implementation checklist:
--
1) Open EC2 Console: Navigate to the Amazon EC2 console at https://console.aws.amazon.com/ec2/.
2) Locate Volume: In the navigation pane, choose Volumes.
3) Attach Volume: Select the volume (must be in 'available' state) and select Actions, then Attach volume.
4) Select Instance: Choose the instance from the dropdown menu (ensure they are in the same Availability Zone).
5) Device Name: Specify a device name (e.g., /dev/sdf) and click Attach volume.

Note: EBS volumes must be in the same Availability Zone as the EC2 instance to be attached
