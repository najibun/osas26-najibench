# osas26-najibench
Docker Stack for openSUSE Asia Summit 2026

## Overview

This repository contains the Docker stack used for the live demonstration and benchmarking experiment for:

**Which Linux Distribution Performs Best for Containerized WordPress?**

The stack runs:

- WordPress
- MariaDB
- Docker Compose
- Netdata

## Quick Start

### 1. Install Docker

Follow the official Docker documentation for your Linux distribution:

https://docs.docker.com/engine/install/

For openSUSE, refer to the openSUSE Docker documentation:

https://en.opensuse.org/Docker

> This repository does not provide Docker installation instructions. It focuses on the application stack used for the experiment.

### 2. Clone the repository

```
git clone https://github.com/najibun/osas26-najibench.git
cd osas26-najibench
```
### 3. Start the stack
```
docker compose up -d
```
4. Check running containers
```
docker compose ps
```
5. Access WordPress

Open the server IP address in your browser:
```
http://YOUR_SERVER_IP:8080
```
