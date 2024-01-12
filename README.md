# Dockerized FastAPI Application

This repository contains a basic FastAPI application that has been containerized using Docker. It demonstrates the fundamental principles of Dockerizing Python applications and ensures reproducibility, consistency, and ease of deployment.

## Key Concepts Learned

- **Containerization with Docker**: Utilizing Docker to create a consistent and isolated environment for the FastAPI application, ensuring that it runs the same way on any Docker-supported platform.
- **Dockerfile Creation**: Crafting a Dockerfile to define the steps for creating a Docker image, including setting up the environment, installing dependencies, and specifying how to run the application.
- **Using Pipenv for Dependency Management**: Implementing Pipenv to manage the application's Python dependencies, providing a clear separation between production and development requirements.
- **Volume Mounting in Docker**: Leveraging Docker volumes to synchronize files (like `Pipfile.lock`) between the host and the container for seamless development and deployment.
- **Service Orchestration with Docker Compose**: Simplifying the deployment process by using Docker Compose to define and run multi-container Docker applications.

## Quick Start Guide

1. **Build and Run with Docker Compose**:

   ```bash
   docker-compose up --build
   ```
This command builds the Docker image and starts the FastAPI service.

2. **Access the Application**:

The FastAPI application will be available at `http://localhost:8080`.

## Project Structure

- `main.py`: The main FastAPI application file.
- `Pipfile` and `Pipfile.lock`: Pipenv files for managing Python dependencies.
- `Dockerfile`: Dockerfile to build the Docker image.
- `docker-compose.yml`: Docker Compose file to define and run the Dockerized application.

## Dependencies

- FastAPI
- Uvicorn
- Docker
- Docker Compose
- Pipenv
