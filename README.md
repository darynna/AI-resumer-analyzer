# ✨ Hireloom — AI Resume Analyzer

<div align="center">

**AI-powered resume analysis that helps you optimize your CV for your dream job.**

Analyze your resume against a specific job description, get an ATS score, and receive actionable AI-powered feedback to improve your chances of getting noticed.

</div>

---

## 🚀 Live Demo

🔗 **[View Live Demo](YOUR_DEPLOYMENT_URL)**

> Upload your resume, enter the job you're applying for, and let Hireloom analyze it.

---

## ✨ Features

### 🤖 AI Resume Analysis
Get personalized feedback based on the job you're applying for rather than generic resume advice.

### 📊 ATS Compatibility Score
See how well your resume performs against Applicant Tracking System criteria.

### 🎯 Job-Specific Analysis
Provide:
- Company name
- Job title
- Job description

The AI evaluates your resume in the context of the specific position.

### 📄 PDF Resume Processing
Upload a PDF resume and automatically convert it into an image for preview and analysis.

### 📈 Detailed Resume Scoring

Your resume is evaluated across multiple categories:

- Tone & Style
- Content
- Structure
- Skills
- ATS compatibility
- And more

### 💡 Actionable Feedback
Instead of simply giving you a score, Hireloom provides recommendations for improving your resume.

### 🖼️ Resume Preview
View your uploaded resume alongside the analysis results.

### 🔐 Authentication
User authentication is handled through Puter.

### ☁️ Cloud Storage
Resume files and generated images are stored using Puter's filesystem.

---

## 🛠️ Tech Stack

### Frontend

- React
- TypeScript
- React Router
- Tailwind CSS
- Vite

### AI & Backend Services

- Puter.js
- Claude / AI models
- Puter KV storage
- Puter filesystem

### PDF Processing

- PDF.js
- Canvas API

### Development

- ESLint
- Git
- Docker

---

## 🏗️ Project Structure

```text
AI-resumer-analyzer/
│
├── app/
│   ├── components/
│   │   ├── ATS.tsx
│   │   ├── Details.tsx
│   │   ├── FileUploader.tsx
│   │   ├── Navbar.tsx
│   │   ├── ResumeCard.tsx
│   │   ├── ScoreBadge.tsx
│   │   ├── ScoreCicle.tsx
│   │   ├── ScoreGauge.tsx
│   │   └── Summary.tsx
│   │
│   ├── constants/
│   │   └── index.ts
│   │
│   ├── lib/
│   │   ├── pdf2image.ts
│   │   ├── puter.ts
│   │   └── utils.ts
│   │
│   └── routes/
│       ├── auth.tsx
│       ├── home.tsx
│       ├── resume.tsx
│       └── upload.tsx
│
├── public/
│   ├── icons/
│   ├── images/
│   ├── pdf.worker.min.js
│   └── pdf.worker.min.mjs
│
├── types/
│   ├── index.d.ts
│   └── puter.d.ts
│
├── Dockerfile
├── package.json
├── vite.config.ts
└── README.md
