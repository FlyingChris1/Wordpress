# Wordpress Blog

This repository provides a Docker-based WordPress environment consisting of
a WordPress container and a MySQL database container.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Quickstart](#Quickstart)
- [Usage](#Usage)

## Prerequisites

- Docker engine
- Docker compose

## Quickstart

- Clone the repository

```bash
git clone https://github.com/FlyingChris1/Wordpress.git
cd Wordpress
```

- Edit example.env with your credentials

```bash
nano example.env
```

- convert example.env to .env

```bash
cp example.env .env
```

- Start Docker compose 

```bash
docker compose up -d
```

- access the project

<your IP>:8080

## Usage

- restart Container

```bash
docker compose restart
```

- stop Container

```bash
docker compose down -v
```

- Enter Wordpress Container

```bash
docker compose exec -it wordpress bash
```

- Get Docker Compose logs

```bash
docker compose logs
```