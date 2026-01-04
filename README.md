# 🚀 JobMatch AI

JobMatch AI is a full-stack web application designed to simplify 
the recruitment process by intelligently matching candidates to job postings. 
The system allows users to create profiles, publish text-based posts, post jobs, and apply for 
jobs using cover letters. An AI agent analyzes the relevance between job descriptions 
and candidate cover letters to generate a matching percentage and rank candidates.

---

### 📌 Problem Statement

The traditional job application process involves manual screening of large numbers 
of applications, which is time-consuming and inefficient. Recruiters lack automated tools to 
evaluate how well a candidate’s profile and cover letter match a job role. JobMatch AI addresses this 
issue by introducing an AI-based matching mechanism to assist in candidate evaluation and ranking.

---
### 🎯 Objectives

Provide a platform for job posting and job applications
Enable users to create and manage profiles
Allow text-based content publishing
Automate candidate evaluation using AI
Generate a matching percentage between job posts and cover letters
Rank candidates based on relevance to job requirements

---
### ✨ Features

User registration and authentication
Profile creation and management
Text-based user posts
Job posting functionality
Job application form with cover letter submission
AI-based candidate-job matching
Candidate ranking system
Responsive user interface


---
### 🛠️ Tech Stack

AI Agent (job-match-ai-aiagent)
- Framework: FastAPI,
- AI Integration: Google Generative AI,
- Dependencies: fastapi, uvicorn, google-generativeai, python-dotenv

Backend (job-match-ai-backend)
- Runtime: Node.js
- Framework: Express.js
- Database: MongoDB with Mongoose
- Authentication: JWT with bcryptjs
- Dependencies: express, mongoose, jsonwebtoken, bcryptjs, cors, dotenv, @google/genai, @google/generative-ai

Frontend (job-match-ai-frontend)
- Framework: React
- Build Tool: Vite
- Styling: Tailwind CSS
- UI Components: Radix UI
- Routing: React Router DOM
- Dependencies: react, react-dom, react-router-dom, tailwindcss, @radix-ui components, lucide-react

---
### 🧠 AI Matching Logic (Overview)

When a candidate submits a cover letter:

- The AI agent compares the cover letter text with the job description.
- Keyword relevance and text similarity are analyzed.
- A matching percentage is calculated.

---
### ⚙️ Installation & Setup

AI Agent Setup
- cd ../job-match-ai-aiagent
- pip install -r requirements.txt
- uvicorn app.main:app --reload

Backend Setup
- cd ../job-match-ai-backend
- npm install
- npm run dev

Frontend Setup
- cd ../job-match-ai-frontend
- npm install
- npm run dev

---
### ⭐API Endpoints

Authentication

- POST /api/auth/register - User registration
- POST /api/auth/login - User login
  
Jobs

- GET /api/jobs - Get all jobs
- POST /api/jobs - Create a new job (Employer only)
- GET /api/jobs/:id - Get job details

Applications

- POST /api/applications - Submit job application
- GET /api/applications - Get user's applications
  
Posts

- GET /api/posts - Get all posts
- POST /api/posts - Create a new post


---
### 🚀 Future Enhancements

- Resume file upload support
- Advanced AI/NLP-based matching
- Admin dashboard
- Real-time notifications
- Recommendation system for jobs

---
### 🔗 Repositories
- Frontend Repo:[Frontend](https://github.com/D-2020483/job-match-ai-frontend)
- Backend Repo:[Backend](https://github.com/D-2020483/job-match-ai-backend)
- AI agent Repo:[AI_Agent](https://github.com/D-2020483/job-match-ai-aiagent)

---

### 📸 Interface Screenshots

<img width="450" height="280" alt="Home page" src="https://github.com/user-attachments/assets/9f4ddbd6-d2f3-407f-9fee-47bc93b1a6cf" />
<img width="450" height="280" alt="job page" src="https://github.com/user-attachments/assets/8f1c0e5b-ff0b-4ff5-964c-72fb751b44d7" />
<img width="450" height="280" alt="profile page" src="https://github.com/user-attachments/assets/0fcf8da7-61dd-43b6-bcfc-d78adc2bf1bd" />
<img width="450" height="280" alt="" src="https://github.com/user-attachments/assets/7b4bf29c-0465-457b-9824-4c202b0f9c0e" />
<img width="450" height="280" alt="" src="https://github.com/user-attachments/assets/970f190b-b031-46d0-ba1b-01a9367cce1a" />

---

👩‍💻 Author
- Dinithi Weerasingha
- Frontend & Full-Stack Developer
