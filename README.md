# MEAN App — DevOps Deployment

## Tech Stack
- MongoDB, Express.js, Angular, Node.js
- Docker, Docker Compose, Nginx
- GitHub Actions CI/CD
- AWS EC2 (Ubuntu 22.04)

## Setup Instructions
1. Clone the repo
2. Configure secrets in GitHub
3. Push to main branch to trigger CI/CD
4. Access app at http://YOUR_VM_IP

## Architecture
[diagram or description of nginx → frontend/backend → mongodb]

## Screenshots
[Insert your screenshots here]
```

---

## 🗂️ Final Repository Structure
```
mean-app-devops/
├── backend/
│   ├── Dockerfile
│   └── ... (app code)
├── frontend/
│   ├── Dockerfile
│   ├── nginx.conf
│   └── ... (app code)
├── .github/
│   └── workflows/
│       └── deploy.yml
├── docker-compose.yml
├── nginx-proxy.conf
└── README.md
