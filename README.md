# GitHub Actions Practice

Hands-on practice with **GitHub Actions, CI/CD automation, workflow orchestration, secrets, matrix strategies, Docker image publishing, and self-hosted runners**.

This repository documents practical GitHub Actions workflows built while strengthening DevOps and CI/CD skills.

## What I Practiced

### ⚙️ GitHub Actions

* Workflow triggers
* Jobs and steps
* Multiple jobs and job dependencies
* Conditional execution
* Matrix strategies
* `fail-fast`
* GitHub-hosted runners
* Self-hosted runners
* Workflow status badges

### 🔐 Secrets & Variables

* GitHub Secrets
* Repository variables
* Using secrets securely inside workflows
* Docker Hub authentication

### 🐳 Docker CI/CD

* Building Docker images with GitHub Actions
* Publishing images to Docker Hub
* Commit SHA based image tagging
* `latest` image tagging
* Automated Docker image builds on push

Example image tags:

```text
latest
sha-<short-commit-sha>
```

### 🖥️ Self-Hosted Runners

Configured and tested a **self-hosted GitHub Actions runner on an EC2 instance**.

This helped me understand:

* GitHub-hosted vs self-hosted runners
* Runner labels
* Job execution on custom infrastructure
* Using AWS EC2 as CI/CD compute

## Repository Structure

```text
.github/
└── workflows/
    ├── ...
    
scripts/
├── ...

secret-as-env.yml
self-hosted.yml
package.json
```

The repository contains individual workflows and exercises for different GitHub Actions concepts.

## Key Concepts

```text
Git Push
   ↓
GitHub Actions
   ↓
Workflow
   ↓
Jobs
   ↓
Runner
   ↓
Build / Test / Deploy
```

For container workflows:

```text
Git Push
   ↓
GitHub Actions
   ↓
Docker Build
   ↓
Docker Login
   ↓
Docker Image
   ↓
Docker Hub
```

## Technologies

**CI/CD:** GitHub Actions
**Cloud:** AWS EC2
**Containers:** Docker
**Registry:** Docker Hub
**Automation:** YAML, Shell
**Version Control:** Git, GitHub

## Learning Focus

The goal of this repository is to understand how GitHub Actions can be used to automate real DevOps workflows, from code changes and testing to container image builds and publishing.

This repository is part of my broader **DevOps learning journey**, where I am building hands-on experience with cloud infrastructure, containers, Infrastructure as Code, and CI/CD.

## Related

**90 Days of DevOps:**
https://github.com/SnigdhaChaudhari611/90DaysOfDevOps

---

**DevOps Engineer | AWS | Terraform | Docker | CI/CD**
