+++
title = "1. Virtual Private Gateway - AWS - PGW"
weight = 1
+++


Create a new Virtual Private Gateway - **AWS - PGW**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/330d9412-b5e2-41c2-86ba-66c9f4fa82d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=995063ede3c38fc4203a7a3deb15046968971a8bb05861aa5bd85138c0dea17b&X-Amz-SignedHeaders=host&x-id=GetObject)


Refresh the page if it says "Success" but shows nothing.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d3b02044-81aa-4990-af24-c7140f784c21/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=8727690d47a9b50b14b1f9aa10e3c5d49145daf808cb834001b45c24d8262b7f&X-Amz-SignedHeaders=host&x-id=GetObject)


Select and attach it to **VPC - AWS**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c4bb2bf1-9956-42f9-8d1a-6319b893192e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=e02a7e242f5c012838a658e9cea1b5d326bdfb9592e3371b4b5d8bd01eb47cc3&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit the Route Table - **AWS - Private** so it can route traffic from this VGW.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e4acad0-4c0e-4f11-86b1-bd63fb30145d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=13bd61fd71e6dee7f43fcc3230ffdbaec7e2dc310dc4632d7159afb9b3f6020e&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/424b778e-2ce9-487e-99e5-b179a35f49d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=0c920f7ca1b2bb29ae91b61db4ef8e05f33d5cafd311d7a62f75e5ef7b676565&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/5c412718-7ea4-47b9-b63b-6b0c0f33ebc7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=d29b104cffaec0380f3678f806034f8a864140c5067a30db51f5e3cc3fb9ecf9&X-Amz-SignedHeaders=host&x-id=GetObject)


