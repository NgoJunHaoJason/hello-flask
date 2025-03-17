# Hello World

Practice integrating Flask, Docker, GitHub (Actions) and AWS (ECR and ECS)

## Pre-requisites

- Python >= 3.10
- Docker

## Build

```bash
docker build -t hello-docker .
```

## Run Local

```bash
docker run -it --rm -p 8080:8080 hello-docker
```

## References

1. [How to Dockerize a Flask Application](https://www.freecodecamp.org/news/how-to-dockerize-a-flask-app/)
