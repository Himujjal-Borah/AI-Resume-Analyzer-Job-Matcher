# AI-Resume-Analyzer-Job-Matcher
🚀 AI Resume Analyzer & Job Matcher

An intelligent system that analyzes resumes, extracts skills using AI, and matches them with real-time job opportunities — fully automated using modern workflows.

📌 Overview

This project allows users to upload their resume and receive personalized job recommendations based on their skills.

The system leverages AI + automation to simplify job searching and deliver relevant opportunities directly to the user’s inbox.

✨ Features

📄 Upload resume (PDF support)

🧠 AI-based skill extraction (Google Gemini)

🔍 Real-time job fetching via API

🎯 Smart job matching based on skills

📩 Automated email notifications

🎨 Modern responsive frontend UI

⚡ Fully automated workflow

🧱 Architecture
Frontend (User Upload)
        ↓
Webhook (n8n)
        ↓
PDF Text Extraction
        ↓
AI Skill Extraction
        ↓
Jobs API Fetch
        ↓
Filtering & Matching Logic
        ↓
Email Notification
🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Automation: n8n

AI Model: Google Gemini

API: Remotive Jobs API

Email Service: Gmail API

⚙️ Workflow Breakdown
1. Webhook Trigger

Receives:

Resume file (PDF)

User email

2. File Processing

Extracts text from uploaded resume

3. AI Skill Extraction

Uses AI to extract skills in structured format

4. Job Fetching

Fetches latest jobs from API

5. Matching Logic

Compares skills with job titles

Filters top relevant jobs

6. Email Notification

Sends personalized job recommendations
