+++
title = "1. Virtual Private Gateway - AWS - PGW"
weight = 1
+++


Create a new **Virtual Private Gateway** named **AWS - PGW**:

- Autonomous System Number (ASN): Amazon default ASN
⇒  **Autonomous System Number (ASN)**: Use **Amazon's default ASN** (64512).
An ASN is used in **Border Gateway Protocol (BGP)** to uniquely identify an autonomous system on the internet or within private networks. When selecting this, the Virtual Private Gateway (VGW) will use **Amazon’s default ASN**. When select this, the Virtual Private Gateway (VGW) will use 64512 (Amazon default) as the ASN. If you select Custom ASN and fill 64512 it will be the same as select this option.

![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-649120-image.png)


Refresh the page if it says "Success" but shows nothing.


![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-489188-image.png)


Select and attach it to **VPC - AWS**


![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-586593-image.png)


Edit the Route Table - **AWS - Private** so it can route traffic from this VGW.


![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-188622-image.png)


**`0.0.0.0/0`** is a **catch-all route**, which means it includes **all IP addresses**. Essentially, it says "for any traffic not matched by a more specific route, use this route to VGW", so it will redirect traffic to VGW if no other route/instance matched.


![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-767674-image.png)


![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/24-289401-image.png)


