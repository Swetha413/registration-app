# Registration App

This is a sample Registration App with a Spring Boot backend and a frontend (React/Angular/etc.).

## Project Structure

- `server/` – Backend Spring Boot service
- `webapp/` – Frontend web application
- `regapp-deploy.yml` – Kubernetes deployment for frontend
- `regapp-server.yml` – Kubernetes deployment for backend

## Build & Run with Docker

### Backend
```bash
cd server
docker build -t regapp-server .
docker run -p 8080:8080 regapp-server
