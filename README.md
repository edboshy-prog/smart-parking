# Smart Parking

A Docker Compose project with two services: a dashboard for the security guard and a storage server for the car images taken by the parking lot camera.

![Docker CI](https://github.com/<user>/<repo>/actions/workflows/docker-ci.yml/badge.svg)

## Services

- **web-service** (Nginx, port 8080): serves the HTML dashboard
- **storage-service** (Apache, port 8081): serves the car images, stored in a Docker volume

## Run

```bash
docker compose up --build
```

- Dashboard: http://localhost:8080
- Image: http://localhost:8081/car1.jpg

## Team

- Your Name
- Teammate 1
- Teammate 2
