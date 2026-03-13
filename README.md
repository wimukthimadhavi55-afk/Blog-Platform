# ProTodo - Premium Task Manager

## Group Information
- **Student 1:** Wimukthimadhavi55-afk - Role: DevOps Engineer
- **Student 2:** Sandu500 - Role: Frontend Developer

## Project Description
ProTodo is a modern, responsive Todo List application designed with a premium Glassmorphism aesthetic. It allows users to efficiently manage their daily tasks with features like real-time task counting, filtering (All, Active, Completed), and persistent storage using `localStorage`. The project includes a full CI/CD pipeline integrated with GitHub Actions for automated linting, building, and deployment.

## Live Deployment
🚀 **Live URL:** [https://wimukthimadhavi55-afk.github.io/Blog-Platform/](https://wimukthimadhavi55-afk.github.io/Blog-Platform/)

## Technologies Used
- HTML5 & CSS3 (Custom Glassmorphism Design)
- JavaScript (Vanilla JS for core logic)
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

### Sandu500
- Semantic HTML structure
- Premium CSS Glassmorphism UI implementation
- Mobile responsiveness and accessibility


## Setup Instructions
### Prerequisites
- Node.js (version 18 or higher)
- Git

### Installation
```bash
# Clone the repository
git clone [your-repo-url]

# Navigate to project directory
cd todo-list-application

# Install dependencies (if any)
npm install

# Run development server
npm start
```

## Deployment Process
The project uses GitHub Actions for CI/CD:
1. **CI Pipeline:** On every push or pull request to `main` or `develop`, the project is automatically linted, built, and tested.
2. **Deploy Pipeline:** On every push to the `main` branch, the project is automatically deployed to the production environment (Vercel).

## Build Status
![CI Pipeline](https://github.com/sandu500/Blog-Platform/workflows/CI%20Pipeline/badge.svg)
![Deploy](https://github.com/sandu500/Blog-Platform/workflows/Deploy%20to%20GitHub%20Pages/badge.svg)

---
*Developed as part of the DevOps Assignment.*