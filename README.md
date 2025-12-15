# HTML Form – Docker Practice Project

This is a simple *HTML & CSS based form project*.
The main purpose of this project is to *practice Docker and containerization*, not frontend development.

---

## 🛠 Tech Used

- HTML
- CSS
- Docker
- Nginx (Alpine Image)
- Linux (Ubuntu)
- Git & GitHub

---

## 🎯 Project Objective

- Practice writing Dockerfile
- Serve static HTML using Nginx container
- Understand port binding and container workflow
- Improve hands-on Docker skills for DevOps role

---

## 🐳 Docker Details

- Base Image: nginx:alpine
- Port Mapping: 8083 → 80
- Static files copied inside container

---

## ▶️ Run Project

```bash
docker build -t html-form .
docker run -d -p 8083:80 html-form
