+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-629672-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-471300-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-857777-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-765193-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-161901-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-168389-image.png)


