# Django Notes App - Dockerized
This project is a simple Django Notes App that I built by following tutorials from youtube(Train with Shubham). The project demonstrates how to containerize a notes application using Docker and Docker Compose.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Maniktyagis/Django-notes-app-Dockerized.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
