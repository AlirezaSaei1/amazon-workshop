# Amazon Bootcamp – DevOps Workshop (ML Track)

This repository was created as part of my participation in the **Amazon Bootcamp**. I joined the **Machine Learning (ML)** track and completed the 3-day program, which included technical workshops, career sessions, and a hands-on **DevOps Workshop** on Day 3.

During the DevOps session, I deployed a containerized web application using GitHub, AWS CodePipeline, CodeBuild, and Amazon ECS. This repository contains the code and configuration files used throughout the workshop.

---

## 🚀 What I Did

### 🔧 Setup & Configuration
- Selected an AWS region and configured my IDE/CLI environment.

### 🔁 DevOps Workflow
- Learned about the DevOps model on AWS.
- Set up a GitHub repository for version control.
- Created a secure GitHub connection using the GitHub App integration.
- Configured IAM roles to allow AWS services to interact.
- Defined a container using ECS task definitions.
- Wrote a `buildspec.yml` file to automate build steps.
- Deployed the application to ECS using CodePipeline.
- Set up and tested the pipeline.
- Implemented a rolling deployment strategy.

---

## 📁 Repository Contents

- `buildspec.yml` – CodeBuild build instructions
- `taskdef.json` – ECS task definition
- `imagedefinitions.json` – Container image metadata for ECS
- `appspec.yaml` – CodeDeploy deployment configuration
- `Dockerfile`, `index.html`, `AWS_logo.png` – Application and asset files

---

## 🎯 Purpose

This project helped me understand and apply DevOps practices using AWS tools. I gained hands-on experience with CI/CD pipelines, containerized deployments, and infrastructure-as-code concepts in a real-world DevOps context.

---

Thanks to AWS and the University Engagement team for organizing this impactful workshop!
