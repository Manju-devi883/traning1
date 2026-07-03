# Day 6 - AWS, Docker & Project Introduction

## Objective
The objective of this session was to understand the basics of Amazon Web Services (AWS), learn the fundamentals of Docker and containerization, and get an introduction to the AI project that will be developed during the training.

---

# 1. Amazon Web Services (AWS)

## Theory
Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. It offers various cloud services such as computing, storage, databases, networking, and AI services. Instead of buying physical servers, developers can use AWS resources over the internet.

### Why AWS?
- Scalable infrastructure
- Cost-effective (Pay-as-you-go)
- High availability
- Secure cloud services
- Easy deployment of applications

### Common AWS Services
- EC2 (Virtual Servers)
- S3 (Cloud Storage)
- Lambda (Serverless Computing)
- RDS (Database Service)
- IAM (Identity and Access Management)

### Example
A company hosts its AI chatbot on an AWS EC2 instance so users from anywhere in the world can access it.

---

# 2. Docker

## Theory
Docker is a containerization platform that allows developers to package an application along with all its dependencies into a container. This ensures the application runs consistently across different environments.

### Why Docker?
- Easy application deployment
- Environment consistency
- Lightweight compared to Virtual Machines
- Faster development and testing
- Simplified dependency management

### Basic Docker Workflow

Application

↓

Docker Image

↓

Docker Container

↓

Run Anywhere

### Common Docker Commands

Check Docker version

```bash
docker --version
```

Download an image

```bash
docker pull python
```

View running containers

```bash
docker ps
```

List downloaded images

```bash
docker images
```

### Example
A Python AI application is packaged into a Docker container. The same container runs successfully on both the developer's laptop and the production server without any configuration changes.

---

# 3. Project Introduction

## Project Overview
An introduction to the AI project was provided, including its objectives, architecture, required technologies, and development roadmap.

### Project Goals
- Understand the project workflow
- Identify required tools and technologies
- Plan the implementation steps
- Prepare the development environment

### Technologies to be Used
- Python
- Git & GitHub
- Docker
- AWS
- LLMs
- MCP
- APIs

### Example
An AI assistant project where:
- The backend is developed using Python.
- AI responses are generated using an LLM.
- Docker is used for containerization.
- AWS is used for deployment.

---

# Key Learnings

- Understood the basics of AWS and cloud computing.
- Learned how Docker simplifies application deployment.
- Understood the purpose and roadmap of the AI project.
- Learned how cloud services and containers are used together in real-world AI applications.

---

# Summary

Day 6 focused on the fundamentals of AWS, Docker, and the AI project roadmap. AWS introduced cloud computing concepts, Docker demonstrated how applications can be packaged and deployed consistently, and the project overview provided a clear understanding of the technologies and implementation plan for the upcoming development work.
