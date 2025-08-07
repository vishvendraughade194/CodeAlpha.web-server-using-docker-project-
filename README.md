
# Docker Web Server

A lightweight web server using Docker and Nginx.

## 🚀 Features

- Docker containerization basics
- Deploy Nginx web server in container
- Monitor and manage container lifecycle
- Health monitoring with logs
- Easy scalability with docker-compose

## 🐳 Getting Started

### Build the image

```bash
docker build -t docker-web-server .
```

### Run the container

```bash
docker run -d -p 8080:80 docker-web-server
```

Visit: [http://localhost:8080](http://localhost:8080)

### Using docker-compose

```bash
docker-compose up --build -d
```

### Monitor container

```bash
docker ps
docker logs docker_web_server
```

## 🧹 Stop and remove

```bash
docker stop docker_web_server
docker rm docker_web_server
```
