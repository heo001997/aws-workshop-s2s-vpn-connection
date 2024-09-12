+++
title = "5. EC2 - AWS - EC2 Private"
weight = 5
+++


This form is quite long, so we will fill it out step by step.

- Name: AWS - EC2 Private
- [Amazon Machine Image (AMI)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html): Amazon Linux 2 AMI
⇒ This will be the OS (Operation system) for this EC2 instance. While there is no best AMI, we chose Amazon Linux 2 for **convenience when installing Openswan VPN.**

![image.png](/images/003-iii-setup-vpc-aws-resources/12-269667-image.png)


Create [a key pair to be able to SSH](/5731ccef72a94529839b57e5ee138276) into **AWS - EC2 - Private** if you don’t already have one.


![image.png](/images/003-iii-setup-vpc-aws-resources/12-772176-image.png)


![image.png](/images/003-iii-setup-vpc-aws-resources/12-626002-image.png)


After creating the key pair, you can select it now.


![image.png](/images/003-iii-setup-vpc-aws-resources/12-479040-image.png)


For network settings, we will edit them as follows:

- VPC: AWS
- Subnet: AWS - Private subnet
- Auto-assign public IP: Disable
⇒ This EC2 instance is private and does not need a public IP.
- Select existing security group: AWS - Private
⇒ Our security group will allow **other instances** in the **same private subnet** to **communicate** via ICMP and Ping.

![image.png](/images/003-iii-setup-vpc-aws-resources/12-585400-image.png)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


![image.png](/images/003-iii-setup-vpc-aws-resources/12-848419-image.png)


Now, we’re done setting up the VPC AWS resources!


