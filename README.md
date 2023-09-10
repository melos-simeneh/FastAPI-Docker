# FastAPI with Docker
The projects show how to dockerize the FastAPI application.
## Prerequisites
- Python installed
- Docker Desktop installed
- Python basics
- FastAPI basics
## Installation
To build the docker image:
```
docker build -t fastapi-image .
```
To start the docker image
```
docker run --name fastapi-container -p 8000:80 fastapi-image
```
