# CDD Lab Experiment 8: Docker Images and Containers

## Objective
Create Docker images and containers for simple applications.

## Duration
2 Hours

## Tasks
1. Install Docker.
2. Pull and run an existing image (e.g., `hello-world` or `nginx`).
3. Create a simple application.
4. Write a basic Dockerfile.
5. Build a custom image.
6. Run a container from the custom image.

## Commands Reference
```bash
docker --version
docker pull hello-world
docker run hello-world
docker build -t my-app .
docker run -p 8080:80 my-app
docker images
docker ps
```

## Expected Outcome
A custom Docker image running as a container.
