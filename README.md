# CodeAlpha Web Server Using Docker

## Project Description
This project demonstrates how to deploy and manage a web server using Docker containers.

## Technologies Used
- Docker
- Nginx
- HTML

## Project Files
- `index.html` — Website content
- `Dockerfile` — Instructions to build the Docker image
- `README.md` — Project documentation

## Build Docker Image
```powershell
docker build -t codealpha-webserver .
```

## Run Docker Container
```powershell
docker run -d -p 8080:80 --name codealpha-container codealpha-webserver
```

## Access Website
Open this URL in your browser:

http://localhost:8080

## Container Management
Stop the container:
```powershell
docker stop codealpha-container
```

Start the container:
```powershell
docker start codealpha-container
```

Check running containers:
```powershell
docker ps
```

View container logs:
```powershell
docker logs codealpha-container
```
