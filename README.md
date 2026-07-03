# end-to-end-cicd-pipeline-amazon-ecs
End-to-End CI/CD Pipeline using Jenkins, Docker, Amazon ECS, Amazon ECR, SonarQube, Maven and AWS to automate testing, containerization and deployment of applications.

## Project Overview
This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline built on AWS.

The pipeline automates the software delivery lifecycle from source code commit through automated testing, static code analysis, containerization, image publishing, and deployment to Amazon Elastic Container Service (Amazon ECS).

The objective was to simulate a production-style deployment pipeline using modern DevOps tools and AWS services while applying automation, security, and cloud-native deployment practices.

## Project Objectives
Automate software delivery

Improve deployment consistency

Containerize applications using Docker

Publish images to Amazon ECR

Deploy automatically to Amazon ECS

Implement secure AWS authentication

Improve code quality using SonarQube

Gain practical experience with AWS DevOps services

## Technologies Used
| Technology                | Purpose              |
| ------------------------- | -------------------- |
| GitHub                    | Source Control       |
| Jenkins                   | CI/CD                |
| Maven                     | Build Tool           |
| Java                      | Application          |
| Checkstyle                | Static Code Analysis |
| SonarQube                 | Code Quality         |
| Docker                    | Containerization     |
| AWS CLI                   | AWS Authentication   |
| Amazon ECR                | Container Registry   |
| Amazon ECS                | Container Deployment |
| IAM                       | Security             |
| CloudWatch                | Logging              |
| Application Load Balancer | Traffic Distribution |
| Target Group              | ECS Routing          |
| Linux                     | Jenkins Server       |

## AWS Services Used
Amazon ECS

Amazon ECR

EC2

IAM

CloudWatch

Application Load Balancer

Target Groups

## Pipeline Workflow
Developer commits code

↓

GitHub Webhook

↓

Jenkins Pipeline Starts

↓

Checkout Source Code

↓

Compile using Maven

↓

Execute Unit Tests

↓

Run Checkstyle

↓

Run SonarQube Scan

↓

Validate Quality Gate

↓

Build Docker Image

↓

Authenticate with AWS

↓

Push Image to Amazon ECR

↓

Deploy to Amazon ECS

↓

Application becomes available through Application Load Balancer

## Jenkins Pipeline Stages
Retrieve latest application code from GitHub.

Compile application using Maven.

Execute automated unit tests.

Run static code analysis.

Analyze code quality.

Ensure quality requirements are satisfied before deployment.

Package the application into a Docker container.

Authenticate using IAM credentials stored securely in Jenkins Credentials.

Upload Docker image to Amazon Elastic Container Registry.

Update ECS Task Definition

Deploy latest image

Start new ECS Tasks

Register tasks with Target Group

Application becomes available through the Load Balancer

## Jenkins Configuration
Installed Jenkins

Configured Global Tools

Installed Plugins

Configured Credentials

Connected GitHub

Created Pipeline Job

## Docker
Installed Docker Engine

Configured Docker Service

Added Jenkins user to Docker group

## AWS CLI
Installed AWS CLI

Configured AWS Credentials

## Amazon ECR
Created ECR Repository

Configured IAM Permissions

## Amazon ECS
Created ECS Cluster

Created Task Definition

Created ECS Service

Configured Container Definition

Configured Desired Tasks

## Load Balancer
Created Application Load Balancer

Configured Listener

Created Target Group

Registered ECS Service

## CloudWatch
Configured ECS Log Groups

Verified Application Logs

## Skills Demonstrated
AWS

Amazon ECS

Amazon ECR

Docker

Jenkins

CI/CD

Cloud Computing

Automation

Linux

GitHub

SonarQube

Maven

IAM

CloudWatch

Application Load Balancer

DevOps

## Lessons Learned
This project strengthened my understanding of:

• End-to-end CI/CD automation
• Docker containerization
• Amazon ECS deployments
• Amazon ECR image management
• Secure IAM authentication
• Cloud-native deployment workflows
• Application Load Balancer configuration
• CloudWatch logging
• DevOps best practices

## Future Improvements
Infrastructure as Code using Terraform

Deploy to Amazon EKS

Implement Kubernetes

GitHub Actions

GitLab CI/CD

ArgoCD

GitOps

Blue/Green Deployments

Prometheus

Grafana

AWS Lambda

## Author
Nokuthula Patience Zulu

Cloud & DevOps Engineer in Development

📍 Pretoria, South Africa

GitHub:
https://github.com/Nok2lapatience

LinkedIn:
https://linkedin.com/in/Nokuthula-zulu-762a4157
