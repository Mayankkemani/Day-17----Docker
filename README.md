# 🐳 Day 17 – Docker Introduction

## 📖 Overview

Today, I started my Docker journey by learning the fundamental concepts of containerization. I installed Docker, explored Docker Architecture, understood the difference between Images and Containers, connected my Docker CLI with Docker Hub, and successfully ran my first Docker container.

---

# 📚 Topics Covered

## 🐳 What is Docker?

Docker is a containerization platform that packages an application along with its dependencies into a lightweight container, allowing it to run consistently across different environments.

---

## 📦 What is a Container?

A Docker Container is a lightweight, isolated runtime environment that contains:

- Application
- Runtime
- Libraries
- Dependencies
- Configuration

Containers ensure applications run the same way on any machine.

---

## 🖼️ What is a Docker Image?

A Docker Image is a read-only template used to create Docker Containers.

**Image → Template**

**Container → Running Instance of Image**

---

## ⚙️ Docker Architecture

```
Developer
     │
Docker CLI
     │
Docker Daemon
     │
Docker Image
     │
Docker Container
```

---

## 🔄 Docker Workflow

```
Developer
     │
Docker Build
     │
Docker Image
     │
Docker Hub
     │
Docker Pull
     │
Docker Run
     │
Application Running
```

---

# 📥 Docker Installation

Verified Docker installation and Docker service.

### Commands

```bash
docker --version

docker info

sudo systemctl status docker
```

---

# 🚀 Running the First Container

Successfully ran the first Docker container.

### Command

```bash
docker run hello-world
```

Learned how Docker automatically:

- Contacts Docker Daemon
- Downloads the Image from Docker Hub
- Creates a Container
- Runs the Container
- Displays the output

---

# 🖼️ Docker Images

Viewed locally available Docker Images.

### Command

```bash
docker image ls
```

Observed:

- hello-world
- mysql

---

# 🌐 Docker Hub

Created a Docker Hub account.

Username:

```
Mayankkemani
```

Logged into Docker Hub.

### Command

```bash
docker login
```

Learned:

- Public Images can be pulled without login.
- Login is required to push your own Docker Images.
- Private repositories require authentication.

---

# 📖 Important Concepts Learned

## Docker vs Virtual Machine

- Containers are lightweight.
- Containers share the Host OS Kernel.
- Virtual Machines have their own complete Operating System.

---

## Image vs Container

| Image | Container |
|--------|-----------|
| Template | Running Image |
| Read-only | Running Instance |
| Static | Dynamic |

---

## Docker Client vs Docker Daemon

Docker Client sends commands.

Docker Daemon executes those commands by creating and managing containers.

---

## Docker Hub vs GitHub

| GitHub | Docker Hub |
|---------|------------|
| Stores Source Code | Stores Docker Images |
| git push | docker push |
| git clone | docker pull |

---

# 💻 Commands Practiced

```bash
docker --version

docker info

docker run hello-world

docker image ls

docker login

sudo systemctl status docker
```

---

# 🎯 Outcome

Today I successfully:

- Installed and verified Docker.
- Understood Docker Architecture.
- Learned Docker Images and Containers.
- Ran my first Docker Container.
- Created a Docker Hub account.
- Logged into Docker Hub.
- Explored locally stored Docker Images.

This marks the beginning of my Docker and Containerization journey for DevOps.

---

## 🚀 Next Step

➡️ Day 18 – Docker Images & Containers

- docker pull
- docker run
- docker ps
- docker stop
- docker start
- docker restart
- docker rm
- docker exec
- docker logs

#Docker #DevOps #Containers #DockerHub #Linux #Cloud #Automation #LearningInPublic
