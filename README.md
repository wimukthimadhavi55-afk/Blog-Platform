# ProTodo - Premium Task Manager

## Group Information
- **Student 1:** ITBNM-2313-0090[S.A.Madhavi]- Role: DevOps Engineer
- **Student 2:** ITBNM-2313-0080[Saduni malka] - Role: Frontend Developer

## Project Description
ProTodo is a modern, responsive Todo List application designed with a premium Glassmorphism aesthetic. It allows users to efficiently manage their daily tasks with features like real-time task counting, filtering (All, Active, Completed), and persistent storage using `localStorage`. The project includes a full CI/CD pipeline integrated with GitHub Actions for automated linting, building, and deployment.

## Live Deployment
🚀 **Live URL:** [https://wimukthimadhavi55-afk.github.io/Blog-Platform/](https://wimukthimadhavi55-afk.github.io/Blog-Platform/)

## Technologies Used
- HTML5 & CSS3 (Custom Glassmorphism Design)
- JavaScript (Vanilla JS for core logic)
- Express.js (Backend Server Configuration)
- Docker & Docker Compose (Containerization)
- GitHub Actions (CI/CD Pipeline)
- Node.js (Development environment)
- Vercel/Netlify (Deployment platform)
- Google Fonts (Outfit Typography)

## Features
- **Add Tasks:** Create new tasks with ease.
- **Delete Tasks:** Remove completed or unwanted tasks.
- **Mark Complete:** Toggle task status with smooth animations.
- **Filter Tasks:** Easily switch between All, Active, and Completed views.
- **Persistent Storage:** Tasks are saved to the browser's local storage.
- **Task Counter:** Real-time feedback on remaining active tasks.
- **Responsive UI:** Fully optimized for mobile and desktop screens.
- **Cross-Platform Execution:** Run seamlessly using Docker containers and Express.js server.

## Branch Strategy
We implemented the following branching strategy:
- `main` - Production branch (Deployment)
- `develop` - Integration branch (Merging features)
- `feature/*` - Individual feature development branches

## Individual Contributions
### Wimukthimadhavi55-afk
- Repository setup and configuration
- GitHub Actions CI/CD pipeline implementation
- Deployment setup and management
- Initial project structure and documentation
- Docker setup and Express Server integration

### Sandu500
- Semantic HTML structure
- Premium CSS Glassmorphism UI implementation
- Mobile responsiveness and accessibility

## Setup Instructions

### Option 1: Run with Docker (Recommended)
You can easily spin up the application using Docker and Docker Compose on any platform.
1. Make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed.
2. Clone the repository and navigate into the folder:
```bash
git clone https://github.com/wimukthimadhavi55-afk/Blog-Platform.git
cd Blog-Platform
```
3. Run the application:
```bash
docker-compose up -d --build
```
*The app will be accessible at: `http://localhost:3000`*

### Option 2: Run Locally (Node.js)

#### Prerequisites
- Node.js (version 18 or higher)
- Git

#### Installation
```bash
# Clone the repository
git clone https://github.com/wimukthimadhavi55-afk/Blog-Platform.git

# Navigate to project directory
cd Blog-Platform

# Install dependencies
npm install

# Run the Express server
npm start
```
*The app will be accessible at: `http://localhost:3000`*


## Deployment Process
The project uses GitHub Actions for CI/CD:
1. **CI Pipeline:** On every push or pull request to `main` or `develop`, the project is automatically linted, built, and tested.
2. **Deploy Pipeline:** On every push to the `main` branch, the project is automatically deployed to the production environment (Vercel).

## Build Status
![CI Pipeline](https://github.com/sandu500/Blog-Platform/workflows/CI%20Pipeline/badge.svg)
![Deploy](https://github.com/sandu500/Blog-Platform/workflows/Deploy%20to%20GitHub%20Pages/badge.svg)

---
*Developed as part of the DevOps Assignment.*
