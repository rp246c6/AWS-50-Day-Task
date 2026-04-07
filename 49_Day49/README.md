--------
Terminal 1
---------
ping <private ip> -c 5

sssh into public instance
ssh -i .ssh/devops-key.pem ec2-user@public ip

ssh into private ip
ssh ubuntu@private ip

copy private key to id_rsa
cp .ssh/datacenter-key.pem id_rsa

mv id_rsa .ssh/

ssh ubuntu@private ip -J ec2-user@publicip

 ssh ec2-user@<public instance private ip>
 
 ssh-keygen -t ed25519
 cat .public
 
 ssh ec2-user@publicip
 exit
 
 crontab -e
 * * * * * /usr/bin/scp /var/log/boots.log ubuntu@10.20.1.134:~/boot/boots.log

 -------------
 terminal 2
 ------------
 ssh ec2-user@publicip
 vim .ssh/authorized_keys
 paste the key from from public id of private instance
 mkdir boot
 cd boot/
 ls 
 ls -ld boot/
 cat boots.log
 crontab -e
 sudo yum install cronie
 crontab -e
 * * * * * aws s3 cp ~/boot/boots.log s3://datacenter-s3-logs-4000/datacenter-priv-vpc/boot/boots.log
 
