# Deploying-Multi-Tier-Website-On-EC2

## Problem Statement:
Company ABC wants to move their product to AWS. They have the following things setup right now.
1.	MySQL DB
2.	Website PHP
The company wants high availability on this product, therefore wants auto-scaling to be enabled on this product. 

## First let's start by understanding a few key terms :
## What is EC2?

EC2 stands for Elastic Compute Cloud, which is a web service provided by Amazon Web Services (AWS). EC2 is a central part of AWS and offers scalable computing capacity in the cloud. It allows users to rent virtual servers, known as instances, on a pay-as-you-go basis. These instances can be easily configured and scaled based on the user's computing requirements. EC2 instances come with a variety of instance types optimized for different use cases, such as compute-optimized, memory-optimized, storage-optimized, and more. Users have full control over their instances, including the ability to start, stop, terminate, and configure them. EC2 is widely used for hosting applications, websites, and for running various types of workloads in the cloud. It provides flexibility, scalability, and reliability for computing resources in the AWS cloud environment.

## What is a Multi-Tier Website?
Multi-tier website refers to a web architecture that is organized into different layers or tiers, each serving a specific function in the overall operation of the site. The three main tiers are the presentation layer (or user interface), the business logic layer, and the data layer. The presentation layer is what users see and interact with on the website. The business logic layer contains the application's logic and rules, handling tasks like processing user inputs and making decisions. The data layer manages the storage and retrieval of information from databases. This architectural approach helps in creating a scalable, modular, and maintainable web system, where changes or updates in one tier do not necessarily affect the others.

## What is RDS?
Amazon RDS (Relational Database Service) is a fully managed database service offered by Amazon Web Services (AWS), enabling users to easily set up, operate, and scale relational databases in the cloud. Supporting various database engines such as MySQL, PostgreSQL, Oracle, and Microsoft SQL Server, RDS automates routine administrative tasks like backups and patching, allowing users to focus on application development. With features like scalability, high availability through Multi-AZ deployments, security enhancements, and the option for read replicas, RDS provides a reliable and efficient solution for organizations seeking a cloud-based, hassle-free relational database management system.

## What is AutoScaling?
Auto Scaling in AWS is a service that automatically adjusts the number of compute resources (such as EC2 instances) in a group to match the desired capacity specified by the user. The primary goal of Auto Scaling is to ensure that you have the right amount of resources available to handle varying workloads, helping to maintain application availability and manage costs effectively.

## What is an Auto-Scaling Group?
Auto Scaling Groups (ASG) in AWS allow for the automatic adjustment of the number of EC2 instances based on application demand. By defining policies tied to metrics like CPU utilization or network traffic, ASGs dynamically scale instances up or down, ensuring optimal performance and resource utilization. These groups distribute instances across multiple Availability Zones for increased fault tolerance, and they seamlessly integrate with features like Elastic Load Balancing and AWS CloudWatch for efficient load distribution and monitoring. ASGs simplify the management of instances, offering a scalable and resilient solution that adapts to changing workloads in a cost-effective manner.


	




	




	





