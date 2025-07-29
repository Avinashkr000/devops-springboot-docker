# Spring Boot Docker Demo 🚀

This is a simple Spring Boot application containerized using Docker. It is part of my DevOps learning practice (Week 1).

## 🔧 Tech Stack
- Java 21
- Spring Boot 3.5.4
- Maven
- Docker

## 📦 How to Build and Run

### Step 1: Build the Spring Boot application

```bash
mvn clean package
Step 2: Build Docker Image
bash
Copy
Edit
docker build -t springboot-app:v1 .
Step 3: Run the Docker Container
bash
Copy
Edit
docker run -p 8080:8080 springboot-app:v1
Open in browser: http://localhost:8080

🐳 Push to DockerHub
bash
Copy
Edit
docker tag springboot-app:v1 avinashkr000/springboot-app:v1
docker push avinashkr000/springboot-app:v1

Author: Avinash Kumar
GitHub: github.com/avinashkr000
DockerHub: hub.docker.com/u/avinashkr000
