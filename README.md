# Dockerized WordPress Deployment: Simplified Setup with Compose


## Overview

This repository provides a simplified setup for deploying WordPress using Docker Compose. By utilizing Docker containers, you can easily deploy and manage a WordPress instance along with its dependencies in a consistent and isolated environment.

## Features

- Docker Compose setup for deploying WordPress.
- MySQL database integration for data persistence.
- Easily customizable and scalable deployment.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone the repository:

   ```sh
    git clone https://github.com/mahmoud-sabra/Dockerized-WordPress-Deployment-Simplified-Setup-with-Compose.git
2. Navigate to the repository directory:
   ```
    cd Dockerized-WordPress-Deployment-Simplified-Setup-with-Compose
   ```
3. Create a .env file based on the provided env.example with your actual secret values.
   ```
    cp env.example .env  
   ```
4. Start the WordPress deployment:
   ```
    docker-compose up -d
   ```
5. Access the WordPress site in your web browser:
   ```
   http://localhost:80
   ```
6. When you're done, you can stop the services:
   ```
   docker-compose down
   ```
