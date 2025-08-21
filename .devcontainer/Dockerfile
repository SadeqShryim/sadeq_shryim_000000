# Base devcontainer image
FROM mcr.microsoft.com/devcontainers/universal:2

# Install Mongo + Python + Node setup
RUN sudo apt-get update && \
    sudo apt-get install -y mongodb && \
    pip3 install --no-cache-dir django && \
    npm install -g npm@latest

WORKDIR /workspace

EXPOSE 27017 3000
