# Lab 1 — Getting Started with Docker

**Course:** 04800 Special Topics: AIOps Observability, Spring 2026    

---

## Overview

This lab covers foundational Docker skills including building and running
containers, managing images and volumes, using Docker Compose, and deploying
the Google Online Boutique microservices application using Skaffold.

---

## Screenshots

| # | File | Description |
|---|------|-------------|
| 1 | [01_our_application.png](01_our_application.png) | `docker ps` and `docker image ls` output alongside the running Todo app with items added |
| 2 | [02_updating_app.png](02_updating_app.png) | Todo app with modified title in CAPS demonstrating live container rebuild |
| 3 | [03_sharing_app.png](03_sharing_app.png) | Docker Hub showing successfully pushed image under waithaka001/lab1-getting-started |
| 4 | [04_persisting_db.png](04_persisting_db.png) | Docker Desktop Volumes panel showing the todo-db named volume |
| 5 | [05_bind_mounts.png](05_bind_mounts.png) | Container running with bind mount; testfile.txt visible in host app directory |
| 6 | [06_docker_compose.png](06_docker_compose.png) | `docker compose ps` output showing multi-container app running |
| 7 | [07_remote_container.png](07_remote_container.png) | Shell session inside container: env vars (MYSQL_*), process list, and MySQL connection confirmed |
| 8 | [08_boutique_image_ls.png](08_boutique_image_ls.png) | Full set of Boutique microservice images locally rebuilt via Skaffold (tagged `sic-jss-475-g11a66b24`) |
| 9 | [09_boutique_homepage.png](09_boutique_homepage.png) | Online Boutique frontend running at localhost:8080 using local Docker images |
