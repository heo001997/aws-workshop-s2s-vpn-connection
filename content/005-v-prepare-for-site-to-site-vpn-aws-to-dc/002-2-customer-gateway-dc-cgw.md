+++
title = "2. Customer Gateway - DC - CGW"
weight = 2
+++


Next, create a **Customer Gateway** to represent your on-premises data center’s endpoint in the VPN connection.

- BGP ASN: 65000
⇒ It’s important that the **ASN for the VGW and CGW** be **different**, even though both typically use private ASNs from the same range. If both the VGW and the CGW were configured with the same ASN (e.g., 64512), BGP would not work correctly because each autonomous system (network) must have a unique ASN to properly exchange routes.
	- **VGW Default ASN**: Typically **64512**.
	- **CGW ASN**: Often **65000** (or any private ASN from 64512 to 65534), but it can be customized based on your on-premises network's requirements.
- IP address: 54.85.149.143
⇒ This is YOUR **DC - EC2 - Openswan Gateway IPv4 Public Address,** the same one we used for the SSH check.
- Certificate ARN: None
⇒ This is a unique identifier for an **SSL/TLS certificate** that you manage in **AWS Certificate Manager (ACM)** or **AWS Identity and Access Management (IAM)**. The ARN is used to reference the certificate in AWS services such as **Elastic Load Balancing (ELB)**, **CloudFront**, **API Gateway**, and others.
- Device: None
⇒ You can name the device as needed, but this field is optional.

![image.png](/images/005-v-prepare-for-site-to-site-vpn-aws-to-dc/25-565005-image.png)


