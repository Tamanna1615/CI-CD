# CI/CD Pipeline using GitHub Actions and OpenShift

## Project Overview
This project demonstrates the implementation of a complete Continuous Integration and Continuous Delivery (CI/CD) pipeline using GitHub Actions, Tekton pipelines, and OpenShift. The goal of this project is to automate the build, test, and deployment process of a sample application by applying CI/CD concepts learned throughout the course.

The pipeline ensures that code changes are automatically tested and deployed, improving software reliability and reducing manual intervention.

---

## Objectives
- Implement Continuous Integration using GitHub Actions
- Automate unit testing using a CI workflow
- Use Tekton for task orchestration in OpenShift
- Deploy the application using an OpenShift pipeline
- Validate successful execution through logs and pipeline status

---

## Tools and Technologies Used
- GitHub Actions
- Tekton Pipelines
- OpenShift
- Docker
- Node.js / Python (based on sample application)
- YAML

---

## CI/CD Pipeline Workflow
1. Code is pushed to the GitHub repository.
2. GitHub Actions workflow is triggered automatically.
3. The workflow installs dependencies and runs unit tests.
4. Tekton tasks are executed for build and cleanup operations.
5. OpenShift pipeline deploys the application.
6. Application logs confirm successful deployment.

---

## Repository Structure
