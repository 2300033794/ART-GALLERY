# ART-GALLERY

# ART GALLERY CRUD OPERATION PROJECT WITH CI/CD AND DOCKER

This project is a Full Stack CRUD Application developed using:

- React + Vite (Frontend)
- Spring Boot + Java (Backend)
- MySQL (Database)
- Docker (Containerization)
- Git & GitHub (Version Control)
- CI/CD Workflow Commands

---

# Project Structure

## Backend

```bash
OnlineArt
```

This folder contains:
- Spring Boot Backend
- REST APIs
- Controller
- Service
- Repository
- MySQL Database Connection

---

## Frontend

```bash
onlineartgallery
```

This folder contains:
- React Frontend
- UI Components
- CRUD Operations Pages
- API Integration

---

# Technologies Used

## Frontend Technologies

- React
- Vite
- Bootstrap
- JavaScript
- HTML
- CSS

---

## Backend Technologies

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

---

## DevOps & Tools

- Docker
- Git
- GitHub
- VS Code

---

# Frontend Setup

## Step 1: Move to Frontend Folder

```bash
cd onlineartgallery
```

---

## Step 2: Install Frontend Dependencies

```bash
npm install
```

This installs:
- React packages
- Vite
- Bootstrap
- Node Modules

---

## Step 3: Run Frontend

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

If port is busy:

```bash
http://localhost:5174
```

---

# Backend Setup

## Step 1: Move to Backend Folder

```bash
cd OnlineArt
```

---

## Step 2: Run Spring Boot Backend

```bash
mvn spring-boot:run
```

OR run directly from:
- VS Code
- IntelliJ IDEA

Backend runs on:

```bash
http://localhost:8080
```

---

# Database Setup Using Docker

# What is Docker?

Docker is a container platform used to run applications and databases inside isolated containers.

In this project:
- MySQL Database runs inside Docker Container.
- Spring Boot connects to MySQL Container.

---

# Docker Hub Website

Go to:

```bash
https://hub.docker.com/
```

Docker images are downloaded from Docker Hub.

---

# Install Docker Desktop

Download Docker Desktop from:

```bash
https://www.docker.com/products/docker-desktop/
```

Install and start Docker Desktop before running containers.

---

# Verify Docker Installation

Run:

```bash
docker --version
```

Check running Docker service:

```bash
docker ps
```

---

# Pull MySQL Docker Image

Download official MySQL image from Docker Hub:

```bash
docker pull mysql:8.0
```

This downloads:
- MySQL Server
- Required container files
- Linux image environment

Image source:

```bash
https://hub.docker.com/_/mysql
```

---

# Create MySQL Docker Container

Run:

```bash
docker run --name mysql-service ^
-e MYSQL_ROOT_PASSWORD=root ^
-e MYSQL_DATABASE=art ^
-p 3306:3306 ^
-d mysql:8.0
```

---

# Explanation of Docker Command

## docker run

Creates and starts a new container.

---

## --name mysql-service

Container name:

```bash
mysql-service
```

---

## -e MYSQL_ROOT_PASSWORD=root

Sets MySQL root password:

```bash
root
```

---

## -e MYSQL_DATABASE=art

Automatically creates database:

```bash
art
```

---

## -p 3306:3306

Maps:
- Local machine port
- Docker container port

MySQL default port:

```bash
3306
```

---

## -d

Runs container in detached/background mode.

---

## mysql:8.0

Docker image name and version.

---

# Check Running Containers

```bash
docker ps
```

Shows:
- Container ID
- Running Status
- Ports
- Container Name

---

# Check All Containers

```bash
docker ps -a
```

Shows:
- Running containers
- Stopped containers

---

# Start Docker Container

```bash
docker start mysql-service
```

---

# Stop Docker Container

```bash
docker stop mysql-service
```

---

# Restart Docker Container

```bash
docker restart mysql-service
```

---

# Remove Docker Container

```bash
docker rm mysql-service
```

---

# Open Docker Container Terminal

```bash
docker exec -it mysql-service bash
```

This opens Linux terminal inside container.

---

# View Docker Logs

```bash
docker logs mysql-service
```

Used for:
- Error checking
- MySQL startup logs
- Debugging

---

# View Docker Images

```bash
docker images
```

Shows downloaded images.

---

# Remove Docker Image

```bash
docker rmi mysql:8.0
```

Deletes MySQL image from local system.

---

# CI/CD Commands Used

# Maven Build

```bash
mvn clean install
```

Used for:
- Cleaning old build files
- Compiling project
- Running tests
- Creating JAR/WAR file

---

# Run Spring Boot Backend

```bash
mvn spring-boot:run
```

Starts backend application.

---

# Frontend Dependency Installation

```bash
npm install
```

Installs frontend packages.

---

# Run Frontend

```bash
npm run dev
```

Starts React Vite development server.

---

# Frontend Production Build

```bash
npm run build
```

Creates optimized production build.

---

# Git Commands Used

# Initialize Git Repository

```bash
git init
```

---

# Add Files to Git

```bash
git add .
```

---

# Commit Changes

```bash
git commit -m "Initial commit"
```

---

# Connect GitHub Repository

```bash
git remote add origin https://github.com/2300033794/ART-GALLERY.git
```

---

# Change Branch Name

```bash
git branch -M main
```

---

# Push Project to GitHub

```bash
git push -u origin main --force
```

---

# Push Future Changes

```bash
git add .
git commit -m "Updated project"
git push
```

---

# Features

- Add Art
- Update Art
- Delete Art
- View Art
- Full CRUD Operations
- Frontend and Backend Integration
- Dockerized MySQL Database
- CI/CD Workflow Commands
- GitHub Version Control

---

# Workflow of Project

## Step 1
Start Docker Desktop.

---

## Step 2
Run MySQL Docker Container.

---

## Step 3
Start Spring Boot Backend.

---

## Step 4
Start React Frontend.

---

## Step 5
Frontend sends API requests to Backend.

---

## Step 6
Backend connects to MySQL Docker Container.

---

## Step 7
CRUD Operations performed successfully.

---

# Author

Vijay Sai
