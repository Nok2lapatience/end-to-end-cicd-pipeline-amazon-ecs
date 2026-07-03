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

