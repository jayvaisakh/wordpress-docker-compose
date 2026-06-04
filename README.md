# WordPress Deployment using Docker Compose

## Overview

This project demonstrates how to deploy a complete WordPress environment using Docker Compose.

The setup includes:

* WordPress container
* MySQL database container
* Docker networking
* Persistent storage using Docker volumes

This project was implemented and tested on Ubuntu WSL using Docker.

---

# Technologies Used

* Docker
* Docker Compose
* WordPress
* MySQL 8.0
* Ubuntu WSL

---

# Project Structure

```text
wordpress-docker/
├── docker-compose.yml
├── README.md
├── .gitignore
├── screenshots/
├── docs/
└── backups/
```

---

# Docker Compose Configuration

The project uses two containers:

## WordPress Container

* Official WordPress image
* Port mapping for browser access
* Connected to MySQL service

## MySQL Container

* MySQL 8.0 image
* Environment variables for database setup
* Persistent Docker volume for database storage

---

# Running the Project

## Clone Repository

```bash
git clone <repository-url>
cd wordpress-docker
```

## Start Containers

```bash
docker-compose up -d
```

## Verify Running Containers

```bash
docker ps
```

---

# Access WordPress

Open browser:

```text
http://localhost:8081
```

Complete the WordPress installation setup from the browser.

---

# Stop Containers

```bash
docker-compose down
```

---

# Screenshots

## Running Containers

Add screenshots inside the `screenshots/` folder.

---

# Learning Outcomes

Through this project, I learned:

* Multi-container Docker applications
* Docker Compose orchestration
* Container networking
* Persistent storage using Docker volumes
* Port mapping
* WordPress container deployment

---

# Author

Vaisakh J

