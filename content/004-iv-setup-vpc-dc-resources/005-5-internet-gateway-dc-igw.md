+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-629381-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-970022-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-387014-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-886104-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-909467-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-434643-image.png)


