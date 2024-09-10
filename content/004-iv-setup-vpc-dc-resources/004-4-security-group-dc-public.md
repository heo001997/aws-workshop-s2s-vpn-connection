+++
title = "4. Security Group - DC - Public"
weight = 4
+++


Fill out the form and click "Create." This will **allow any client (computer, laptop, server, etc.)** to **ping all EC2 instances** in the **DC - Public Subnet** if they can "see" each other.


Since this is a **public subnet**, the resources (e.g., EC2) inside will be **exposed to the internet**. I will allow **SSH** for all EC2 instances in this public subnet by setting **Inbound rules - SSH**.


**Only allow My IP** to SSH because we don’t want these EC2 instances to be accessible by any IPs other than my current one.


![image.png](/images/004-iv-setup-vpc-dc-resources/17-842851-image.png)


