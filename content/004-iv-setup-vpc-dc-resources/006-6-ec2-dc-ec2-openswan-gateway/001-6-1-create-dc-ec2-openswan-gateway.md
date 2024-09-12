+++
title = "6.1 Create DC - EC2 Openswan Gateway"
weight = 1
+++


This form is quite long, so we will fill it out step by step.


![image.png](/images/004-iv-setup-vpc-dc-resources/006-6-ec2-dc-ec2-openswan-gateway/20-526200-image.png)


Create a key pair to be able to SSH into AWS - EC2 - Private if you don’t already have one.


![image.png](/images/004-iv-setup-vpc-dc-resources/006-6-ec2-dc-ec2-openswan-gateway/20-654405-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/006-6-ec2-dc-ec2-openswan-gateway/20-455664-image.png)


Select the newly created key pair.


![image.png](/images/004-iv-setup-vpc-dc-resources/006-6-ec2-dc-ec2-openswan-gateway/20-311724-image.png)


Edit Network like this

- Auto-assign public IP: Enable
⇒ This is a **Public EC2 instance**, so it must have a **public IP** to allow connections.

![image.png](/images/004-iv-setup-vpc-dc-resources/006-6-ec2-dc-ec2-openswan-gateway/20-158615-image.png)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


