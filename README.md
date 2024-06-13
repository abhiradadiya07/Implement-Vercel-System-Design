# Vercel Deployment Service Clone


## Tech Stack

- Node.JS
- AWS S3,ECS and ECR
- Redis
- Docker
- React
- Shadcn

### Setup Guide

This Project contains following services and folders:

- `api-server`: HTTP API Server for REST API's
- `build-server`: Docker Image code which clones, builds and pushes the build to S3
- `s3-reverse-proxy`: Reverse Proxy the subdomains and domains to s3 bucket static assets

### System Architecture

![Vercel Clone System Architecture](https://i.imgur.com/r7QUXqZ.png)
