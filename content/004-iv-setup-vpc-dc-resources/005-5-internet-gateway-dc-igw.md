+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2dc2ede2-912f-4c54-983f-33230a1e25f6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192238Z&X-Amz-Expires=3600&X-Amz-Signature=b5e0cbdc632be6494a81aed2682b0a83e61428275bf40f43043b303f79bf17b8&X-Amz-SignedHeaders=host&x-id=GetObject)


Attach it to **VPC - DC**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/bc9962b3-3b6b-4146-95ec-fa20b3e0417e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192238Z&X-Amz-Expires=3600&X-Amz-Signature=57b9ff91ea24e763abdb860228659077200a2122ebf3efe8a8e69c7da8bb7a1c&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9d52f744-bcd0-419e-aef7-9cf1383ae06d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192238Z&X-Amz-Expires=3600&X-Amz-Signature=18cbcd210a483c3fd62042498c2d933feb1234d02d89d4b51c450e2c6fc7a7e6&X-Amz-SignedHeaders=host&x-id=GetObject)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/df0364d1-faff-4346-a66f-bd7c3f361296/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=f993ad896c22f0b065283528041c00e70750c9d5e85a6f221b254f15076ea209&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/8d516c8e-c307-4d41-8060-10080477035f/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=791e2f951730ce74b23404f059a7a5010fb0c13c65f3265d9d7b5fa5fec2f22c&X-Amz-SignedHeaders=host&x-id=GetObject)


The route should look like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/950790c5-069b-4222-9591-a8819bd38aa7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=2b52e987b991d76d27bd73ec4c244fad896d293b225cfb7439a3f8d1656edbc3&X-Amz-SignedHeaders=host&x-id=GetObject)


