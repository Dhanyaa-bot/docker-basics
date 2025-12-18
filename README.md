# docker-basics

 output - https://github.com/Dhanyaa-bot/docker-basics/blob/main/docker1.png
<br>
# Docker Basics – Static Web App using Nginx

## 📌 Project Overview
This project demonstrates Docker fundamentals by containerizing a simple static web application using **Nginx**.  
The application is built as a Docker image and run as a container, exposing the app on a local port.

This project is part of my **DevOps learning journey**, focusing on hands-on implementation and debugging.

---

## 🛠 Tech Stack
- Docker
- Nginx (Alpine)
- HTML
- Windows + WSL2 (Docker Desktop)

---

##how to run <br>
docker build -t docker-basics-nginx .
<br>
##how to run container<br>
docker run -d -p 8080:80 docker-basics-nginx

<br>
##how to access the application <br>
http://localhost:8080

<br>


