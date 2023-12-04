# DevOps frontend with Angular
This project is a forntend application developed using the Angular framework for a DevOps pipeline. The application is designed to seamlessly integrate with various DevOps tools to automate processes such as continuous integration, testing, deployment, and monitoring. The key components of this project include Angular, Jenkins, Nexus, Docker, Prometheus, and Grafana
## Setup

Clone the repository:
```bash
git clone https://github.com/OlfaJlali/DevOps_Project_Front
cd DevOps_Project_Front
```
Build the project:
```bash
ng serve --open
```


## Usage

#### 1- Push changes to the repository to trigger the Jenkins build.
#### 2- Monitor the build status in Jenkins.
#### 3-Deploy the application using Docker and Nexus.
#### 4-Monitor application metrics in Grafana.


## Features
The core of the project is a frontend application developed with angular, providing a scalable and efficient foundation.

### Jenkins Integration with Webhook: 
The application is integrated with Jenkins to automate the continuous integration and deployment processes. Jenkins is configured with a webhook to trigger builds automatically whenever changes are pushed to the repository.


### Artifact Repository with Nexus: 
The project artifacts are stored in Nexus, a repository manager, to facilitate versioning, distribution, and deployment of the application.

### Containerization with Docker: 
The application is containerized using Docker, providing a consistent and isolated environment for deployment. Docker images are created and stored in Nexus for seamless deployment.

### Monitoring with Prometheus and Grafana: 
The application is monitored using Prometheus for collecting metrics, and Grafana for visualizing these metrics. This ensures real-time visibility into the performance and health of the application.

