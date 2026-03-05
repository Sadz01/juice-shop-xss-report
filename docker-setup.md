# Docker Setup Guide – Juice Shop

This guide explains how to deploy OWASP Juice Shop locally using Docker for vulnerability testing.

---

## Prerequisites

- Docker Desktop installed (DockerDesktop)
- Docker running
- Internet connection to pull the container image

---

## Step 1 - Pull the Official Image

Open a terminal and run:

```bash
docker pull bkimminich/juice-shop
```

---

## Step 2 – Run the Container

```bash
docker run -d -p 3000:3000 bkimminich/juice-shop
```

---

## Step 3 – Access the Application

Open your browser and navigate to:

```bash
http://localhost:3000
```

---

## Step 4 - Stop the Container

To stop the running container, run this in the terminal:

```bash
docker ps
docker stop <container_id>
```

---

## Restarting the Container

To restart the application after stopping, run this in the terminal:

```bash
docker start <container_id>
```

---
