# AWS ECS: How to deploy .NET 7 Web API

## 1. Create a Web API .NET 7 in Visual Studio 2022 Community Edition

Run Visual Studio 2022 and create a new Web API

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/f5d8cb5d-cdc2-4fcd-b2e0-4572914e5a22)

Select the Web API .NET Core template

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/792c5b66-9ace-401f-bb8f-6cef1bdca463)

We set the solution name and the location

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/62ed9296-46da-4f0f-b32b-733ed1c7ffb9)

We select the framework .NET 7, we Enable Docker(for automatically create the dockerfile), we Enable OpenAPI and Use controllers

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/aa807d3b-fac4-4986-a7df-8e09467dac3a)

## 2. Create the docker image and upload it to AWS ECR

We log in to AWS 

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/9f3ba668-f211-4ff8-b230-8363b9c6f9c4)

We navigate to the AWS ECR service

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/8e236978-c8d5-4494-a029-b804b0611721)

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/909d32cc-1239-4c33-9908-228bd3a7895a)

We create a new Public Repository

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/96748a26-35fd-4dc4-bc47-bf11acf8bbfd)

Set the Public repo name

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/e570f7c1-76b1-463b-8373-4ca2458b9f18)

We select the operating systems and system architectures that are compatible with the images in your repository

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/91d44745-9f2e-47bd-b18f-820507bfc989)

![image](https://github.com/luiscoco/AWS_ECS_deploy_.NET_7_Web_API/assets/32194879/bc52e8c5-19ac-4718-82b3-da097f14aa57)



## 3. Create a new Cluster in AWS ECS




## 4. Create a new Task definition in AWS ECS




## 5. Create a new Service in AWS ECS



## 6. Access to the Web API application enpoint




