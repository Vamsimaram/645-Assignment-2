
The goal of this assignment is to containerize a web application, deploy it on a Kubernetes cluster, and establish a CI/CD pipeline to automate builds and deployments.

---

## Key Accomplishments

### 1. Containerization and Deployment on Kubernetes

#### Containerization with Docker
- The web application(survey form) was packaged into a Docker container. 
- A Docker image was created using a `Dockerfile`, and the container was run locally to ensure functionality. 
- The image was then pushed to Docker Hub for storage and accessibility.

#### Kubernetes Deployment
- The application was deployed on a Kubernetes cluster created using Rancher. 
- A baseline configuration of three pods ensured scalability and resiliency. 
- Rancher was used to simplify Kubernetes cluster management.
- The deployment was configured using `deployment.yaml` and `service.yaml` files.

---

### 2. CI/CD Pipeline and Automation

#### GitHub for Source Control
- A GitHub repository was set up to manage source code, configuration files, and deployment scripts.

#### Jenkins for CI/CD
- Jenkins was installed and configured to automate the build and deployment processes. 
- Plugins for Docker, Kubernetes, and Git were used to enable seamless integration. 
- Pipelines were triggered automatically on code changes using Git webhooks and a polling mechanism.
