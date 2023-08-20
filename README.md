# ECS Cats and Dogs

Workshop link:
https://catalog.us-east-1.prod.workshops.aws/workshops/8c9036a7-7564-434c-b558-3588754e21f5/en-US/01-intro

Resources: 
https://github.com/aws-samples/amazon-ecs-for-beginners-catsdogs

Note: Since I use the AWS Free Tier version the services exposed in the following sections are susceptible to change.

## Searching for Love and Happiness
![catsdogs](static/images/intro/catsdogs.svg)
This workshop is designed to educate engineers that might not be familiar with Amazon ECS, Fargate, and possibly even Docker container workflow.

## Amazon ECS
Amazon Elastic Container Service (Amazon ECS) is a **fully managed container orchestration** service. ECS has been a foundational pillar for key Amazon services, it can **natively integrate** with other services such as Amazon Route 53, Secrets Manager, AWS Identity and Access Management (IAM), and Amazon CloudWatch providing you a familiar experience to deploy and scale your containers. ECS allows your applications the flexibility to use a mix of **Amazon EC2** and **AWS Fargate** with Spot and On-Demand pricing options. 

## Purpose
- To understand Amazon ECS **fundermental concepts** and **new features**. 
- To practice **useful tools** for Amazon ECS **management**. 

## AWS services you will use
* Amazon Elastic Container Service (ECS)
* Amazon Elastic Container Resistry (ECR)
* AWS Fargate 
* AWS FireLens
* Amazon CloudWatch
* Auto Scaling
* AWS Identity and Access Management (IAM)
* Amazon CloudFormation
* Amazon EC2
* Amazon Application Load Balancer (ALB)

## Architecture
![Architecture](static/images/intro/architecture.svg)

## We will:
* Deploy AWS CloudFormation stack to set up prerequisites. 
* Manage Docker images of **cats** and **dogs** in Amazon ECR.
* Create Amazon ECS **cluster, task definitions**, and **services**. 
* Choose right **launch type** either **EC2** or **Fargate** for each service.
* Deploy simple containerized application **cats and dogs** path-routed through ALB.
* Monitor ECS cluster and services in Amazon CloudWatch **Container Insights**.
* Centralize **container logs** using **AWS FireLens** and Amazon CloudWatch Logs.
* Scale ECS **services** and **cluster** automatically.

## Start here:
[English]
https://ecs-cats-dogs.workshop.aws/en
