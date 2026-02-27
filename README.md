# Cloud-IoT Fuel Management Infrastructure ☁️⛽

## Overview
This repository contains the infrastructure configuration and deployment files for a Cloud-IoT Automated Fuel Management System. This project was architected as part of my MSc in Cloud and Edge Systems and Applications at Harokopio University of Athens.

*Note: This repository focuses strictly on the infrastructure, container orchestration, and service integration components. The application source code (frontend/backend) is maintained in a separate repository.*

## Tech Stack & Architecture
The infrastructure is designed to handle automated data flow, reliable message brokering, and secure storage without manual intervention.

* **Containerization:** Docker & Docker Compose
* **Message Broker:** RabbitMQ
* **Object Storage:** MinIO
* **IoT Data Flow & Visualization:** Node-RED, ThingsBoard
* **Identity & Access Management:** Keycloak

## My Focus & Key Contributions
* **Containerized Environment:** Utilized `docker-compose` to orchestrate and manage all microservices and dependencies seamlessly.
* **Service Integration:** Configured RabbitMQ for reliable message queuing between the IoT edge devices and the cloud backend.
* **Secure Archiving:** Integrated MinIO for robust and scalable object storage of system documents.
* **Automated Data Processing:** Setup the infrastructure for Node-RED and ThingsBoard to enable an automated pipeline for monitoring fuel consumption.

## Getting Started
To spin up the infrastructure locally, ensure you have Docker and Docker Compose installed, navigate to the directory, and run:

```bash
docker-compose up -d
