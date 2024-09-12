+++
title = "1. Setup Site-to-Site VPN - AWS to DC"
weight = 1
+++


Create the Site-to-Site VPN connection, and fill out the form as follows:

- Target gateway type: Virtual private gateway
- Routing options: Static
⇒ We want to explicitly define the IP addresses to match our architecture diagram.
- Static IP Prefixes**:** You will need to fill in two CIDRs. The first is our **VPC - DC (192.168.0.0/16)**, and the second is **VPC - AWS (10.10.0.0/16)**.
- Local IPv4 Network CIDR: Fill in our **VPC - DC** CIDR **(192.168.0.0/16)**.
- Remote IPv4 Network CIDR: Fill in our **VPC - AWS** CIDR **(10.10.0.0/16)**.

![image.png](/images/006-vi-site-to-site-vpn-aws-to-dc/27-647998-image.png)


After creating the VPN connection, you should see the **new VPN connection** from AWS to DC. While waiting for the VPN to be ready in about 10 minutes, move on to the next steps.


![image.png](/images/006-vi-site-to-site-vpn-aws-to-dc/27-998835-image.png)


