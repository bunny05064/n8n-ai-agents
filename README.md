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

### Author

**Somya Tripathi**
Product & AI Enthusiast | Building AI-Powered Automation Solutions

