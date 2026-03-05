# Cloud Node API Deployment

This project demonstrates how to deploy a Node.js backend application on AWS EC2 using Nginx reverse proxy and PM2 process manager.

## Technologies Used

- AWS EC2
- Node.js
- Nginx
- PM2
- Git & GitHub

## Architecture

The application is deployed on an AWS EC2 instance.

Request flow:

User Browser
     │
     ▼
Public Internet
     │
     ▼
AWS EC2 Instance
     │
     ▼
Nginx (Reverse Proxy - Port 80)
     │
     ▼
Node.js Backend (Port 3000)
     │
     ▼
PM2 Process Manager

## Features

- Node.js backend server
- Reverse proxy using Nginx
- Process management using PM2
- Hosted on AWS EC2
- Code version controlled with Git
- Project stored on GitHub

## Deployment Steps

1. Launch EC2 instance
2. Install Node.js
3. Run backend using PM2
4. Install and configure Nginx
5. Set reverse proxy to Node app
6. Push project to GitHub

## Author

Aniket Udgirkar
