# 🐳 Docker Projects Portfolio

This repository contains beginner-level Docker projects built to practice containerization concepts, including running web apps, web servers, and databases using Docker and Docker Compose.

---

## 📁 Projects Included

### 1. 🚀 Flask App (Containerized Python Web App)
A simple Flask web application running in a Docker container.

- **Tech:** Python, Flask
- **How to Run:**
  ```bash
  cd flask-app
  docker build -t flask-docker .
  docker run -p 5000:5000 flask-docker
