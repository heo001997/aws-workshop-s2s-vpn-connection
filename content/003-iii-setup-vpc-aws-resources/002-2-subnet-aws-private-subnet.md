+++
title = "2. Subnet - AWS - Private subnet"
weight = 2
+++


Fill out the form and click "Create"

- VPC ID: Select the AWS VPC we just created
⇒ This will ensure the Subnet belongs to the VPC.
- Subnet name: AWS - Private subnet
- Availability Zone (AZ): us-east-1a
⇒ Each Subnet will be tied to a single AZ, ensuring high availability.
- IPv4 VPC CIDR block: Select our VPC - AWS
⇒ Subnets must have CIDR blocks within the VPC’s CIDR range.
- IPv4 Subnet CIDR block: 10.10.1.0/24
⇒ Resources in this subnet (e.g: EC2) will have IP ranging from **10.10.1.0 to 10.10.1.255/24** (**256 IPs as displayed,** but only **251 usable**). Breakdown:
	- **Total IPs in 10.10.1.0/24**: 256 IPs (from 10.10.1.0 to 10.10.1.255)
	- **AWS reserved IPs**: 5 IP addresses
		- **10.10.1.0**: Network address
		- **10.10.1.1**: Reserved for the VPC router
		- **10.10.1.2**: Reserved for AWS DNS (or for future use)
		- **10.10.1.3**: Reserved for future use
		- **10.10.1.255**: Broadcast address (not used in AWS but still reserved)

![image.png](/images/003-iii-setup-vpc-aws-resources/9-997725-image.png)


