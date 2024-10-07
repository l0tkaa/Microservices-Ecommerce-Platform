# Microservices-based E-commerce Platform

This is a cloud-native, distributed system designed to simulate a real-world e-commerce application. My goal for this is to demonstrate modern software architecture principles by breaking down the platform into multiple microservices, each responsible for a specific function, such as product management, order processing, user management, and inventory tracking. The Tech Stack I'm using is listed below. 

> [!WARNING] 
> This project is still under development and may contain bugs.


## Features
- **Product Service**: Handles CRUD operations for product management.
- **Order Service**: Manages customer orders and communicates with the Product and Inventory services.
- **Inventory Service**: Tracks product stock and updates inventory based on orders.
- **User Service**: Manages user profiles, authentication, and authorization.
- **Message Queue**: RabbitMQ is used to manage communication between microservices.
- **Containerization**: All services are containerized using Docker.
- **Orchestration**: Kubernetes is used to manage containerized services.
- **Cloud Infrastructure**: Terraform is used to provision and manage cloud resources.

## Tech Stack
- **Backend**: 
  - Java (Spring Boot) for Product and Inventory services.
  - Node.js for Order and User services.
- **Message Queue**: RabbitMQ for microservices communication.
- **Database**: PostgreSQL for relational data.
- **Containerization**: Docker.
- **Orchestration**: Kubernetes for managing microservices.
- **Cloud Infrastructure**: Terraform for provisioning cloud resources.
- **CI/CD**: Jenkins/GitHub Actions (Optional) for continuous integration and deployment.

## Installation

### Prerequisites
- Docker
- Kubernetes (Minikube or any K8s setup)
- RabbitMQ (can be run via Docker)
- PostgreSQL/MySQL
- Terraform
- Java JDK (for Spring Boot services)
- Node.js (for Node.js services)

