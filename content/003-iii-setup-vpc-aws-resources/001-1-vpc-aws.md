+++
title = "1. VPC - AWS"
weight = 1
+++


First things first, fill out the form and click "Create"

- Resources to create: VPC only
⇒ We want to explicitly create the VPC and other resources.
- Name tag: AWS 
⇒ This helps to differentiate between our VPCs.
- IPv4 CIDR block: IPv4 CIDR manual input
⇒ Control the CIDR to match our architecture diagram.
- IPv6 CIDR block: No IPv6 CIDR block
⇒ We aren't using IPv6 in our architecture diagram.
- Tenancy: Default (Shared Tenancy)
⇒ Shared tenancy is sufficient, we don’t actually care about where this VPC hosted on physical servers.

![image.png](/images/003-iii-setup-vpc-aws-resources/8-947968-image.png)


(Optional) Other options that I did not select, I encourage you to explore on your own to gain a deeper understanding. Here are some TLDRs and additional details you might find interesting:

- VPC and more: Allows us to create a VPC along with Subnets, Route tables, Network connections…  [https://docs.aws.amazon.com/vpc/latest/ipam/allocate-cidrs-ipam.html](https://docs.aws.amazon.com/vpc/latest/userguide/create-vpc.html#create-vpc-and-other-resources)
- IPAM-allocated IPv4 CIDR block: Use an IPAM pool to assign IPv4 dynamically [https://docs.aws.amazon.com/vpc/latest/ipam/allocate-cidrs-ipam.html](https://docs.aws.amazon.com/vpc/latest/ipam/allocate-cidrs-ipam.html)
- Amazon-provided IPv6 CIDR block: Amazon will handle the dynamic assignment of IPv6 addresses for you [https://aws.amazon.com/about-aws/whats-new/2023/01/amazon-provided-contiguous-ipv6-cidr-blocks/](https://aws.amazon.com/about-aws/whats-new/2023/01/amazon-provided-contiguous-ipv6-cidr-blocks/)
- IPv6 CIDR owned by me: Use your own public IPv6 [https://docs.aws.amazon.com/vpc/latest/userguide/vpc-migrate-ipv6-add.html](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-migrate-ipv6-add.html)
- **Tenancy** refers to how EC2 instances are hosted on physical servers. There are three types of tenancy:
	- **Shared (Default) Tenancy:** Instances share the underlying physical hardware (like CPU, memory, etc.) with other AWS accounts. This is cost-effective but provides less isolation.
	- **Dedicated Instance:** Instances run on hardware dedicated to your AWS account only, meaning no other AWS customer’s instances share that physical server. However, multiple instances from your account can still share that server.
	- **Dedicated Host:** You have full control over the entire physical server, including instance placement, visibility into the server's physical resources (like CPU cores and sockets), and compliance with licensing requirements.

	[https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/dedicated-instance.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/dedicated-instance.html)


