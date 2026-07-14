# 🎵 Anghamna

A Spotify-inspired music streaming platform built with **Java**, **Spring Boot**, and a **Microservices Architecture**. The application provides a scalable backend for music streaming, user management, and social interactions while leveraging modern cloud-native technologies such as **Docker** and **Kubernetes**.

---

## 🚀 Features

- 🔐 User Authentication & Authorization
- 🎵 Music Library Management
- ▶️ Music Streaming Service
- 👥 Social Features (Follow Users & Interactions)
- 🌐 API Gateway for Request Routing
- ⚡ Scalable Microservices Architecture
- 🐳 Docker Containerization
- ☸️ Kubernetes Deployment
- 🗄️ Independent Databases per Service

---

## 🏗️ Architecture

The application follows a **Microservices Architecture**, where each service is independently developed and deployed.

### Services

- **User Service**
  - User registration & authentication
  - Profile management

- **Music Service**
  - Song management
  - Albums & artists

- **Streaming Service**
  - Audio streaming
  - Media delivery

- **Social Service**
  - User interactions
  - Following system

- **API Gateway**
  - Central entry point
  - Request routing
  - Load balancing

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Cloud
- REST APIs

### Databases
- PostgreSQL
- MongoDB *(if applicable)*

### DevOps
- Docker
- Kubernetes

### Tools
- Maven
- Git
- GitHub

---

## 📂 Project Structure

```text
Anghamna
│
├── api-gateway/
├── user-service/
├── music-service/
├── streaming-service/
├── social-service/
├── docker-compose.yml
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- Java 17+
- Maven
- Docker
- Kubernetes (optional)
- PostgreSQL
- MongoDB *(if used)*

### Clone the Repository

```bash
git clone https://github.com/ahmedkamall1/Anghamna.git
cd Anghamna
```

### Run with Docker

```bash
docker-compose up --build
```

Or start each microservice individually using Maven.

---

## 📸 Screenshots

> Add screenshots or architecture diagrams here.

---

## 🔮 Future Improvements

- Playlist Management
- Song Recommendations
- Search Service
- Real-time Notifications
- Likes & Comments
- JWT Refresh Tokens
- CI/CD Pipeline
- Monitoring with Prometheus & Grafana

---

## 📚 What I Learned

This project strengthened my understanding of:

- Microservices Architecture
- Spring Boot & Spring Cloud
- API Gateway
- Docker & Kubernetes
- Service Communication
- Scalable Backend Design
- RESTful API Development

---

## 👨‍💻 Author

**Ahmed Kamal**

- GitHub: https://github.com/ahmedkamall1
- LinkedIn: *(Add your LinkedIn here)*

---

⭐ If you found this project interesting, consider giving it a star!
