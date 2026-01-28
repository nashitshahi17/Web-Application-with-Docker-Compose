# Web Application with Docker Compose

A full-stack **Notes Web Application** containerized using **Docker and Docker Compose**.  
This project demonstrates how to run a Django backend and a frontend application together using Docker for easy setup, consistency, and deployment.

> 🔹 Original application logic is cloned from an existing repository  
> 🔹 Dockerfile and Docker Compose configuration are created and maintained by me

---

## 🚀 Project Overview

This project is a simple **Notes application** where users can create and manage notes.

- **Backend**: Django (REST-based backend)
- **Frontend**: React (served as a built static build)
- **Containerization**: Docker & Docker Compose

The main goal of this repository is to:
- Dockerize an existing web application
- Run the entire stack using a single command
- Simplify local development and deployment

---

## 🧱 Tech Stack

- **Backend**: Django
- **Frontend**: React
- **Database**: SQLite (default Django DB)
- **Containerization**: Docker, Docker Compose
- **Language**: Python, JavaScript

---

## 📁 Project Structure
Web-Application-with-Docker-Compose/
│
├── backend/ # Django backend
│ ├── api/
│ │ ├── models.py # Note model
│ │ ├── views.py
│ │ ├── urls.py
│ │ └── ...
│ ├── manage.py
│ └── ...
│
├── frontend/ # React frontend
│ ├── build/
│ │ ├── index.html # React production build
│ │ └── static/
│ └── ...
│
├── Dockerfile # Docker image configuration
├── docker-compose.yml # Multi-container setup
├── requirements.txt # Python dependencies
├── README.md # Project documentation
