# ART-GALLERY

## ART GALLERY CRUD OPERATION PROJECT

# CI/CD AND DOCKER 

## Project Structure

### Backend
```bash
OnlineArt
```

### Frontend
```bash
onlineartgallery
```

---

# Technologies Used

## Frontend
- React
- Vite
- Bootstrap

## Backend
- Spring Boot
- Java
- MySQL

---

# Frontend Setup

Move to frontend folder:

```bash
cd onlineartgallery
```

Install dependencies:

```bash
npm install
```

Run frontend:

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

or

```bash
http://localhost:5174
```

---

# Backend Setup

Move to backend folder:

```bash
cd OnlineArt
```

Run Spring Boot application using:

```bash
mvn spring-boot:run
```

or run directly from IntelliJ / VS Code.

Backend runs on:

```bash
http://localhost:8080
```

---

# Features

- Add Art
- Update Art
- Delete Art
- View Art
- Full CRUD Operations
- Frontend and Backend Integration

---

---

# Docker Commands Used

## Pull MySQL Docker Image

```bash
docker pull mysql:8.0
```

---

## Create MySQL Container

```bash
docker run --name mysql-service ^
-e MYSQL_ROOT_PASSWORD=root ^
-e MYSQL_DATABASE=art ^
-p 3306:3306 ^
-d mysql:8.0
```

---

## Check Running Containers

```bash
docker ps
```

---

## Check All Containers

```bash
docker ps -a
```

---

## Start Container

```bash
docker start mysql-service
```

---

## Stop Container

```bash
docker stop mysql-service
```

---

## Remove Container

```bash
docker rm mysql-service
```

---

## Open MySQL Container Terminal

```bash
docker exec -it mysql-service bash
```

---

# CI/CD Commands Used

## Maven Build

```bash
mvn clean install
```

---

## Run Spring Boot Backend

```bash
mvn spring-boot:run
```

---

## Frontend Install Dependencies

```bash
npm install
```

---

## Run Frontend

```bash
npm run dev
```

---

## Frontend Production Build

```bash
npm run build
```

---

# Git Commands Used

## Initialize Git

```bash
git init
```

---

## Add Files

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "Initial commit"
```

---

## Add Remote Repository

```bash
git remote add origin https://github.com/2300033794/ART-GALLERY.git
```

---

## Change Branch

```bash
git branch -M main
```

---

## Push Project

```bash
git push -u origin main --force
```

---

## Push Future Changes

```bash
git add .
git commit -m "Updated project"
git push
```

---

# Useful Docker Commands

## View Docker Images

```bash
docker images
```

---

## Remove Docker Image

```bash
docker rmi mysql:8.0
```

---

## View Docker Logs

```bash
docker logs mysql-service
```

---


# Author

Vijay Sai
