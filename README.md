# CloudDeploy: CI/CD with GitHub Actions and AWS S3

This repository contains materials for a hands-on workshop on Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and AWS S3 for static website hosting.

## Overview

This workshop introduces students to the concepts of CI/CD and demonstrates how to implement automated workflows using GitHub Actions to deploy a static website to AWS S3. The presentation covers fundamental concepts, practical examples, and best practices for implementing CI/CD in real-world projects.

## Live Demo Website

This repository includes a fully functional static website that is automatically deployed to AWS S3 whenever changes are pushed to the main branch. The website demonstrates:

- Basic HTML/CSS/JS structure
- Visual representation of the CI/CD pipeline
- Dynamic deployment information

## Contents

- **Presentation**: Markdown slides covering CI/CD concepts and GitHub Actions implementation
- **Working Example**: A complete static website with deployment workflow
- **S3 Deployment Guide**: Step-by-step instructions for setting up AWS S3 hosting
- **GitHub Actions Workflow**: Ready-to-use workflow file for automated deployment

## Topics Covered

1. **Introduction to CI/CD**
   - What is Continuous Integration?
   - What is Continuous Deployment/Delivery?
   - Benefits of CI/CD in software development

2. **GitHub Actions Fundamentals**
   - Understanding workflows, jobs, and steps
   - Triggers and events
   - Actions and the marketplace

3. **Building Your First Workflow**
   - Basic workflow structure
   - Common use cases
   - Testing and validation

4. **Advanced GitHub Actions**
   - Environment variables and secrets
   - Matrix builds
   - Caching dependencies
   - Artifacts and releases

5. **CI/CD Best Practices**
   - Security considerations
   - Performance optimization
   - Workflow organization

## Getting Started

1. Clone this repository
2. Review the presentation slides in the `CICD_GitHub_Actions_Presentation.md` file
3. Explore the example website code in `index.html`, `css/styles.css`, and `js/script.js`
4. Check out the GitHub Actions workflow in `.github/workflows/deploy-to-s3.yml`
5. Follow the deployment guide in `S3_Static_Website_Deployment_Guide.md` to set up your own S3 bucket

## Prerequisites for Students

- Basic understanding of Git and GitHub
- Familiarity with at least one programming language
- GitHub account

## Additional Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
- [CI/CD Best Practices Guide](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)

## Workshop Information

### Repository Name
**github-actions-s3-workshop**

### Talk/Workshop Title
**"CloudDeploy: Automating Website Deployment with GitHub Actions and AWS S3"**

### Target Audience
- Computer Science students
- Web development students
- DevOps beginners
- Anyone interested in automating deployment processes

### Workshop Duration
- 2-3 hours (including hands-on exercises)

### What Students Will Learn
- Setting up a GitHub repository with GitHub Actions
- Configuring AWS S3 for static website hosting
- Creating and understanding CI/CD workflows
- Implementing automated deployments
- Securing AWS credentials in GitHub Secrets
- Best practices for web deployment automation

## License

This project is licensed under the MIT License - see the LICENSE file for details.