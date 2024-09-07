+++
title = "6.1 Create DC - EC2 Openswan Gateway"
weight = 1
+++


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/68379cf6-81c1-4bdd-b50c-97f882a75c39/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=31f16d968862f58649c1d22c4c8e2a3c7308e518ccc8eb4276d8084dc47db9f2&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into AWS - EC2 - Private if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e8f3b13-abe4-476a-9702-c922dd617d30/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=dfb267ee085f050b2b6bda1811e397efe606fcb7242e4038e092f5b2d6ad7a18&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2de80525-c893-42fc-babd-52d67f9add5b/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=047bf3638c13b241f5fa96564f7349260d9b3e78de9b10f4baedd2db75fa38e7&X-Amz-SignedHeaders=host&x-id=GetObject)


Select the newly created key pair.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/19e053e9-2c19-4295-9a2f-b7329afb1be8/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=490296d14eb9308808dcc2a3be1e9f2e84efee2626990920ac7021868d028975&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit Network like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3b2c7b64-dabe-43be-9af1-318c8bab86cc/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T192239Z&X-Amz-Expires=3600&X-Amz-Signature=8721638c3f395cb6b83516fce6741ad1b6b8bc973c45f6a363c1192b65ce9739&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


