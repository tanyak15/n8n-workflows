# Resume Screening & AI Calling Automation

An end-to-end candidate pre-screening system using AI resume analysis and automated phone interviews.

---

## 🔍 Problem It Solves
Recruiters spend hours manually screening resumes and conducting initial calls.

This workflow automates both steps using AI.

---

## ⚙️ Workflow Overview

1. Candidate submits a form:
   - Resume upload
   - Job description selection

2. Resume is extracted and analyzed using an LLM:
   - Skill matching
   - Relevance scoring
   - Screening questions generation

3. All details are stored in **Google Sheets**.

4. If shortlisted:
   - **Retell.ai** initiates an AI-powered phone call

5. After the call:
   - LLM analyzes the conversation
   - Extracts meaningful insights
   - Updates the candidate record

6. Candidate receives an automated email with screening status.

---

## 🧠 AI Capabilities
- Resume-to-JD matching
- Dynamic interview question generation
- Call transcript analysis
- Hiring recommendation logic

---

## 🛠 Integrations Used
- n8n Forms
- Google Drive & Sheets
- OpenAI / LLM
- Retell.ai
- Gmail API
- Webhooks

---

## 📸 Screenshots
Workflow and call analysis screenshots available in `screenshots/`.

---

## ✅ Use Cases
- Recruitment teams
- HR automation platforms
- AI hiring pipelines
