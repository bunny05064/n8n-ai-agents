# Recruit-AI 🤖

Recruit-AI is an AI-powered recruitment automation system designed to streamline the hiring process by automating resume screening, candidate evaluation, communication, and recruitment analytics.

Built using **n8n, Google Gemini, JavaScript, Gmail API, and Webhooks**, the system reduces repetitive recruiter tasks and helps teams make faster, more consistent hiring decisions.

---

## 🚀 Key Features

### AI Candidate Analysis

* Analyze resumes against job descriptions
* Generate candidate fit scores (0–100)
* Identify strengths and skill gaps
* Create candidate summaries
* Recommend next hiring actions

### Automated Candidate Actions

* Schedule interviews automatically
* Generate personalized interview invitations
* Send professional rejection emails
* Update candidate statuses in real time

### Recruitment Dashboard

* Track total candidates
* Monitor interview recommendations
* View rejection and review statistics
* Calculate average fit scores
* Display recent recruitment activity

---

## 🛠 Tech Stack

* **Workflow Automation:** n8n
* **AI Model:** Google Gemini
* **Backend Logic:** JavaScript
* **Email Automation:** Gmail API
* **Data Storage:** n8n Data Tables
* **API Layer:** Webhooks

---

## ⚙️ Workflow

```text
Resume + Job Description
            ↓
   Candidate Analysis Agent
            ↓
      AI Evaluation
            ↓
      Fit Score & Insights
            ↓
       Candidate Database
            ↓
      Decision Engine
      ↙            ↘
Interview      Rejection
      ↘            ↙
     Email Automation
            ↓
 Recruitment Dashboard
```

---

## 📌 API Endpoints

### Analyze Candidate

```http
POST /recruit-ai/analyze
```

### Candidate Actions

```http
POST /recruit-ai/action
```

### Dashboard Metrics

```http
POST /recruit-ai/candidates
```

---

## 📊 Sample Output

```json
{
  "candidateName": "John Doe",
  "fitScore": 87,
  "recommendedAction": "SCHEDULE_INTERVIEW",
  "strengths": "React, Node.js, Leadership",
  "gaps": "Limited AWS experience"
}
```

---

## 🎯 Highlights

✅ Multi-Agent AI Architecture

✅ Resume-to-Decision Automation

✅ Personalized Candidate Communication

✅ Real-Time Hiring Analytics

✅ Event-Driven API Design

✅ Structured AI Output Processing

✅ End-to-End Recruitment Workflow

---

## 📈 Business Impact

* Reduces manual resume screening time
* Improves recruiter productivity
* Standardizes candidate evaluation
* Enhances candidate communication
* Provides actionable recruitment insights

---

## 🔮 Future Enhancements

* ATS Integration
* Resume Parsing with OCR
* Candidate Ranking Engine
* RAG-based Candidate Search
* Interview Feedback Analysis
* Recruiter Copilot Chat Interface

---
## 📸 Workflow Screenshots

### Candidate Analysis Agent
Analyzes resumes against job descriptions, generates fit scores, identifies strengths and gaps, and recommends hiring actions.



<img width="1464" height="783" alt="Screenshot 2026-06-03 at 7 03 50 AM" src="https://github.com/user-attachments/assets/919a80ff-d244-45b5-be41-1c3efd31185f" />


### Candidate Action Agent
Automates interview scheduling and rejection workflows with personalized AI-generated emails.

<img width="1470" height="787" alt="Screenshot 2026-06-03 at 7 09 36 AM" src="https://github.com/user-attachments/assets/d59fd0e8-4de3-4ce0-a07d-c9b6108d030f" />


### Dashboard & Metrics Agent
Provides real-time recruitment insights including candidate counts, interview recommendations, rejection rates, and average fit scores.

<img width="1467" height="790" alt="Screenshot 2026-06-03 at 7 07 54 AM" src="https://github.com/user-attachments/assets/f580c405-d2b1-4054-b70d-5e539d3a24b2" />

## 🏗️ System Architecture

```text
                        Recruit-AI

      Resume + Job Description Input
                    │
                    ▼
        Candidate Analysis Agent
                    │
                    ▼
            Google Gemini AI
                    │
                    ▼
        Candidate Evaluation Data
                    │
                    ▼
             Candidate Database
                    │
        ┌───────────┴───────────┐
        │                       │
        ▼                       ▼
Interview Decision      Rejection Decision
        │                       │
        ▼                       ▼
 AI Interview Email      AI Rejection Email
        │                       │
        └───────────┬───────────┘
                    ▼
              Gmail API
                    │
                    ▼
          Candidate Communication

                    │
                    ▼

         Dashboard & Metrics Agent
                    │
                    ▼
        Recruitment Analytics



