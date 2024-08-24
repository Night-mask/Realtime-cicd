Real-Time CI/CD Pipeline for Node.js Web Application

This project demonstrates a real-time CI/CD pipeline for a Node.js web application, leveraging Jenkins for automated builds, dependency management, and security scanning. The pipeline is integrated with Docker for containerization and OWASP Dependency Check for identifying vulnerabilities.

 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Screenshots](#screenshots)

Project Overview

This project automates the build, testing, and deployment of a Node.js web application using Jenkins pipelines. The pipeline automates processes from Git checkout to container deployment, enhancing development efficiency and security.

Features

- Automated Builds: Jenkins automates the building of the Node.js application.
- Dependency Management: Manages Node.js dependencies with `npm`.
- Security Scanning: Integrates OWASP Dependency Check to identify vulnerabilities.
- HTML Reports: Security scan results are published in HTML format.
- Docker Integration: Builds Docker images and pushes them to Docker Hub.
- End-to-End Automation: From Git checkout to Docker container deployment.

Prerequisites

- Jenkins: Ensure Jenkins is installed and running.
- Node.js: Node.js must be installed on the Jenkins server.
- Docker: Docker must be installed on the Jenkins server.
- GitHub Account: To clone the repository.
- Docker Hub Account: To push Docker images.


file:///home/elangovan/Pictures/Screenshots/Screenshot%20from%202024-08-24%2010-10-53.png

file:///home/elangovan/Pictures/Screenshots/Screenshot%20from%202024-08-24%2010-12-06.png

file:///home/elangovan/Pictures/Screenshots/Screenshot%20from%202024-08-24%2010-13-37.png

