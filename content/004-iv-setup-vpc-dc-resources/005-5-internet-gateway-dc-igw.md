+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-511206-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-344302-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-120655-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-296945-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-424843-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-716862-image.png)


