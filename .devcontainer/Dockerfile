FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Instalar Docker CLI y Docker Compose
RUN apt-get update && \
    apt-get install -y docker.io docker-compose && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
