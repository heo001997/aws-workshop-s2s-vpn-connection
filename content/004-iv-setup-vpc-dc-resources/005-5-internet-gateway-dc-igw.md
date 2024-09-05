+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-622528-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-140834-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-823252-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-352334-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-166920-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-922247-image.png)


