+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Although we created a **Security Group (for SSH and Ping)** and a **Route Table (for IP routing)**, we still need an **Internet Gateway** to allow EC2 instances to connect to the internet.


Create an **Internet Gateway (IGW)** called **DC - IGW** to enable the **DC - VPC** to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-480850-image.png)


Attach the **Internet Gateway** to **VPC - DC** and go back to the **Route Table** to edit it so that it accepts the newly attached **Internet Gateway**.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-738665-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-134086-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-105801-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-263853-image.png)


The route should look like this:

- Destination: **0.0.0.0/0**
	- Target: **DC - IGW**

![image.png](/images/004-iv-setup-vpc-dc-resources/18-363277-image.png)


