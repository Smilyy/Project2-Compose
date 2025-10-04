# Project2-Compose
**Secure DevOps – Assignment 2 (ISEC6000)**

This repository contains the **Docker Compose configuration** for running a containerized **Jenkins CI/CD environment** with **Docker-in-Docker (DinD)** support.  
It forms **Task 2** of the assignment, providing the infrastructure for building, testing, scanning, and deploying a Node.js application in a secure, automated pipeline. 
Created by Laura Jiang.

---

## Repository Structure

| File | Description |
|:------|:-------------|
| `docker-compose.yml` | Defines services for **Jenkins** and **Docker-in-Docker (DinD)**, plus volumes for persistent Jenkins data and Docker layer cache. |
| `.env.example` | Template listing required environment variables (DockerHub credentials, Snyk token etc.). Sensitive values are **not included**. |
| `.gitignore` | Ensures local configs and temp files (like `.env`) are not committed. |
| `README.md` | Documentation for setup and usage. |

---

## How to Run Jenkins with Docker Compose

1. **Clone this repository**
   ```bash
   git clone https://github.com/Smilyy/Project2-Compose.git
   cd Project2-Compose
