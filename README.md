# The_Book_Cellar_public

# Note:
This repo contains project report & screenshots only. It is a public repository. The main repository containing the project code is private. 

# Contents:
The Organization contents below repos:
# faas
Function as a service - Lambda function / Serverless

# infrastructure
Infrastructure as a service - Terraform code

# webapp
Shopping cart for buying & selling books using Nodejs

# ami
Amazon machine Image run using CircleCi

# Introduction

•	Developed books shopping cart using Nodejs & MYSQL hosted on AWS RDS, book images saved in S3 bucket, created AMI using HashiCorp’s Packer, implemented CICD using Terraform & CircleCi, configured AWS cloud deploy agent, generated logs & custom metrices in AWS dashboard using AWS CloudWatch, configured application load balancer, enabled autoscaling, managed DNS using AWS route 53
•	Created password reset functionality for registered users via email generated through a Lambda function (FaaS), SES and SNS topic. Inserted an entry in DynamoDB for that particular user with a TTL of 15 mins
•	Improved website’s security by importing SSL certificate in AWS Certificate manager & encrypting AWS RDS connections


# Technologies User:

Node.js, 
MYSQL, 
Sequelize, 
AWS, Terraform, 
Packer, 
CircleCi, 
CICD
