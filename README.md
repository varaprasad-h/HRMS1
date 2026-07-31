# 🚀 Human Resource Management System (HRMS)

![License](https://img.shields.io/badge/License-MIT-green)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![React](https://img.shields.io/badge/React-Frontend-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange)

---

# 📌 Project Overview

HRMS (Human Resource Management System) is a full-stack web application that helps organizations manage employees, authentication, HR operations, and administrative tasks through a centralized dashboard.

The project is designed with a scalable architecture and can be deployed using modern DevOps practices including Docker, AWS, Jenkins, GitHub Actions, and Nginx.

---

# ✨ Features

- Employee Management
- Authentication & Authorization
- HR Dashboard
- User Profile Management
- REST APIs
- Responsive UI
- MongoDB Database
- Secure Login
- Production Ready Deployment

---

# 🛠 Technology Stack

## Frontend
- React.js
- HTML5
- CSS3
- JavaScript

## Backend
- Node.js
- Express.js

## Database
- MongoDB

## DevOps
- Docker
- AWS EC2
- GitHub Actions
- Jenkins
- Nginx
- PM2

---

# 📂 Project Structure

```
HRMS/

├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── middleware/
│   └── package.json
│
├── server.js
├── package.json
└── README.md
```

---

# 🏗 System Architecture

```
                Users
                  │
                  ▼
          React Frontend
                  │
                  ▼
              Nginx Server
                  │
                  ▼
         Node.js + Express API
                  │
                  ▼
             MongoDB Database
```

---

# ☁ AWS Deployment Architecture

```
                Internet
                    │
                    ▼
          AWS Security Group
                    │
                    ▼
             Amazon EC2 Instance
                    │
        ┌───────────┴───────────┐
        │                       │
        ▼                       ▼
    Nginx Server          Docker Container
                                │
                                ▼
                        Node.js Application
                                │
                                ▼
                          MongoDB Atlas
```

---

# 🚀 Local Installation

Clone Repository

```bash
git clone https://github.com/varaprasad-h/HRMS1.git

cd HRMS1
```

Install Dependencies

Backend

```bash
cd server
npm install
```

Frontend

```bash
cd frontend
npm install
```

Run Backend

```bash
npm start
```

Run Frontend

```bash
npm start
```

---

# 🐳 Docker Deployment

Build Docker Image

```bash
docker build -t hrms .
```

Run Container

```bash
docker run -d -p 3000:3000 hrms
```

---

# ☁ AWS Deployment

This project can be deployed using

- AWS EC2
- Docker
- Nginx
- PM2
- GitHub Actions
- Jenkins

Deployment Flow

```
GitHub

↓

GitHub Actions

↓

Jenkins

↓

Docker Build

↓

Amazon EC2

↓

Nginx

↓

Users
```

---

# ⚙ CI/CD Pipeline

```
Developer

↓

GitHub Push

↓

GitHub Actions

↓

Jenkins Pipeline

↓

Docker Image

↓

Deploy to EC2

↓

Application Live
```

---

# 📊 Monitoring

Recommended Tools

- Prometheus
- Grafana
- Node Exporter

---

# 🔐 Security

- JWT Authentication
- Password Encryption
- Environment Variables
- Secure API Access
- Nginx Reverse Proxy

---

# 📈 Future Enhancements

- Kubernetes Deployment
- Helm Charts
- Terraform Infrastructure
- AWS EKS
- Prometheus Monitoring
- Grafana Dashboard
- ArgoCD GitOps

Example

- Login Page
- Dashboard
- Employee List
- Docker Containers
- Jenkins Pipeline
- GitHub Actions
- AWS EC2

---

# 👨‍💻 Contributors

- Vara Prasad Renati
- Team Members

---

# 📜 License

MIT License

---

# ⭐ Support

If you like this project,

⭐ Star the repository.
