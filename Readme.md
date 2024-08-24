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

![Screenshot from 2024-08-24 10-10-53](https://github.com/user-attachments/assets/6a2b0151-94cb-4465-b1fd-522673d68ea9)


![Screenshot from 2024-08-24 10-12-06](https://github.com/user-attachments/assets/5d069bac-1f2f-48f4-b889-5ce76bf39370)

![Screenshot from 2024-08-24 10-13-37](https://github.com/user-attachments/assets/0d000e37-2017-4a47-a01e-07e286a7b33d)

