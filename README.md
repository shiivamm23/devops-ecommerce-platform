# DevOps E-commerce Platform

A containerized e-commerce application with an automated
Jenkins CI/CD pipeline on AWS.

## Technology Stack

- React and Vite
- Node.js and Express
- PostgreSQL
- Docker and Docker Compose
- Jenkins
- GitHub and Docker Hub
- Terraform and AWS EC2
- Trivy and Gitleaks
- AWS CloudWatch

## Architecture

GitHub -> Jenkins -> Security Scans -> Docker Hub
-> AWS EC2 -> Docker Compose

## Features

- Product catalogue
- Shopping cart
- REST API
- PostgreSQL database
- Automated CI/CD
- Infrastructure as Code
- Health checks and rollback

## Security

Secrets are managed outside source control.
The database is not exposed to the public internet.