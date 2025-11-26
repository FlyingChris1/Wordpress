# Wordpress Blog

This repository provides a Docker-based WordPress environment consisting of
a WordPress container and a MySQL database container.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Quickstart](#Quickstart)
- [Usage](#Usage)

## Prerequisites

- Docker engine

## Quickstart

- Clone the repository

```bash
git clone <REPOSITORY_URL>
cd <REPOSITORY_NAME>
```


## Usage

- You need to create a .env file to fill the variables with you secret credentials

```bash
touch <name>.env
```

- Edit the values of the .env file with your information & credentials:

```bash
nano <name>.env
```

```bash
WORDPRESS_DB_NAME=<your DB name>
WORDPRESS_DB_USER=<your DB user>
WORDPRESS_DB_PASSWORD=<your DB password>
WORDPRESS_DB_ROOTPASSWORD=<your DB root password>
WORDPRESS_DB_HOST=<your DB Host>
```

- Start & stop Docker compose 

```bash
docker compose up
docker compose down
```

