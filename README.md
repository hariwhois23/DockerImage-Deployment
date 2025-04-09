#  Day 1 - DevOps Internship @ Elevate Labs

## Task: Automate Code Deployment Using CI/CD Pipeline (GitHub & Actions)

![Alt text](https://miro.medium.com/v2/resize:fit:720/1*FRvPUiHgbXaGHQC023yErA.png)

## Steps Followed
1. **Created a node.JS Application and built a Dockerfile "**
   Dockerfile: A script that defines how to build a Docker image for the Node.js app (includes base image, dependencies, and startup commands).
   
   Docker image: A packaged version of your Node.js app created from the Dockerfile, ready to run in any Docker container.

2. **Created a GitHub Actions Workflow**

   Created a file at `.github/workflows/PushingImageDockerHUB.yml` to define the CI pipeline.

3. **Configured Secrets in GitHub Repository**

   Added the following secrets in **Repository Settings → Secrets and variables → Actions**:
   - `DOCKER_USERNAME` – Docker Hub username
   - `DOCKER_TOKEN` – Docker Hub access token or password (validation period for a week)

4. **Wrote the GitHub Actions Pipeline**
    Refer the `.github/workflows/PushingImageDockerHUB.yml` file for the pipline script
