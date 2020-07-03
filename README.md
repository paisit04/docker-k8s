# Docker and Kubernetes: The Complete Guide

https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide

## Section1
12. But Really...What's a Container?

## Section2
17. Container Lifecycle
24. The Purpose of the IT Flag

## Section3
32. The Build Process in Detail
36. Manual Image Generation with Docker Commit

## Section5
53. Docker Compose Files
54. Networking with Docker Compose
55. Docker Compose Commands
58. Automatic Container Restarts
59. Container Status with Docker Compose

## Section6
68. Creating the Dev Dockerfile
```bash
docker build -f Dockerfile.dev .
```
72. Docker Volumes
74. Bookmarking Volumes
```bash
docker run -it -p 3000:3000 -v /app/node_modules  -v $(pwd):/app CONTAINER_ID
```
76. Shorthand with Docker Compose
77. Overriding Dockerfile Selection
80. Executing Tests
```bash
docker run -it CONTAINER_ID npm run test    
```
82. Docker Compose for Running Tests
85. Need for Nginx
87. Implementing Multi-Step Builds

## Section9
129. Environment Variables with Docker Compose
131. Nginx Path Routing
132. Routing with Nginx
133. Building a Custom Nginx Image
