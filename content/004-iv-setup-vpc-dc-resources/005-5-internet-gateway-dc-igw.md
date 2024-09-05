+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-341527-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-792987-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-786846-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-245816-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-546118-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-312837-image.png)


