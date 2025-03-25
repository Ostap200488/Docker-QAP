# Golf Club Tournament Management API

This project is a full-featured RESTful API for managing golf club **members** and **tournaments**, built with **Spring Boot**, **Gradle**, and **MySQL**, and fully containerized using **Docker** for easy deployment.

---

## 📦 Features

- Add, update, delete, and view **members** and **tournaments**
- Add **members to tournaments**
- Search for members and tournaments using various filters
- MySQL database integration
- Full Docker support (`Dockerfile` + `compose.yaml`)
- Tested via Postman

---

## ⚙️ Technologies

- Java 22
- Spring Boot
- Spring Data JPA
- Gradle
- MySQL 8
- Docker + Docker Compose
- Postman (for API testing)

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Docker & Docker Compose

### Clone and Run

```bash
git clone https://github.com/Ostap200488/Docker-QAP.git
cd Docker-QAP/golf-club-api-master-10
./gradlew build
docker compose up --build
