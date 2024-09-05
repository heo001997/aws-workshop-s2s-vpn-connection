+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-480816-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-314920-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-123019-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-870408-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-867622-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-316104-image.png)


